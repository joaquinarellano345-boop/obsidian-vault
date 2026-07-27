---
tags: [vps, manual, backup, referencia]
created: 2026-07-27
updated: 2026-07-27
---

# 🖥️ Manual Completo del VPS

> **Servidor:** Contabo VPS · Ubuntu 24.04 · Kernel 6.8.0-124-generic
> **IP:** vmi3459918.contaboserver.net
> **Disco:** 193 GB (18 GB usado · 9%)
> **RAM:** 11 GB (2.8 GB usado)
> **SWAP:** No configurado ⚠️

---

## 🌐 Dominios y Subdominios

### Dominio principal
- **hjazzi.com** — Landing + servicios (nginx → proxy 8081, 5030, 5005)
- **www.hjazzi.com** — Redirige a hjazzi.com

### Subdominios activos (20)

#### Tiendas y ecommerce
| Subdominio | Puerto | Tipo | Notas |
|------------|--------|------|-------|
| uropic.hjazzi.com | 5010 | Flask app | Productos importados |
| shangrila.hjazzi.com | 5020 | Flask app | Decoración y hogar |
| estiloyvida.hjazzi.com | 5022 | Flask app | Moda, marca HJAZZI |
| shop.hjazzi.com | 5021 | Flask app | Tienda principal |
| logis.hjazzi.com | 5015 | Flask app | Logística |
| nicolas.hjazzi.com | 5016 | Flask app | Servicios profesionales |
| racion.hjazzi.com | 8082 | Proxy | Ración alimenticia |

#### Sistema y herramientas
| Subdominio | Puerto | Tipo | Notas |
|------------|--------|------|-------|
| evolution.hjazzi.com | 5050/5060 | Static + API | Dashboard + uploads |
| acta.hjazzi.com | 8000 | API | Documentación y actas |
| n8n.hjazzi.com | 5678 | Docker | Automatizaciones |
| app.hjazzi.com | 5020 | Proxy | App central |
| metrics.hjazzi.com | - | Static | Métricas |
| lab.hjazzi.com | - | Static | Laboratorio |
| ai.hjazzi.com | - | Static | Proyectos AI |
| agents.hjazzi.com | - | Static | Documentación agentes |
| academy.hjazzi.com | - | Static | Academia |

#### Especiales
| Subdominio | Puerto | Tipo | Notas |
|------------|--------|------|-------|
| cv.hjazzi.com | - | Static | Portfolio CV |
| editor.hjazzi.com | - | Static | Editor de imágenes |
| elgallo.hjazzi.com | - | Static | Demo ferretería |
| paleta.hjazzi.com | - | Static | Estudio de color |

---

## ⚙️ Servicios Systemctl

### Hermes (core agent)
- `hermes-gateway` — Gateway principal (8765)
- `hermes-dashboard` — Dashboard web (5050)
- `hermes-upload` — Upload de archivos (5060)

### Tiendas (6 servicios Flask)
- `uropic.service` — Puerto 5010
- `shangrila.service` — Puerto 5020
- `estiloyvida.service` — Puerto 5022
- `logis.service` — Puerto 5015
- `nicolas.service` — Puerto 5016
- `leadcapture.service` — Captación de leads

### Infraestructura
- `acta-core.service` — API de actas (8000)
- `nginx.service` — Proxy reverso (80, 443)
- `docker.service` — Contenedores
- `ssh.service` — Acceso remoto (22)
- `cron.service` — Tareas programadas

### Docker
- `n8n-n8n-1` — n8n (127.0.0.1:5678)

---

## 🔌 Mapa de Puertos

| Puerto | Servicio | Externo |
|--------|----------|---------|
| 22 | SSH | ✅ |
| 53 | DNS | ✅ |
| 80 | nginx HTTP | ✅ |
| 443 | nginx HTTPS | ✅ |
| 5010 | UROPIC | ❌ local |
| 5015 | Logis | ❌ local |
| 5016 | Nicolás | ❌ local |
| 5020 | Shangrilá | ❌ local |
| 5021 | Shop | ❌ local |
| 5022 | Estilo y Vida | ❌ local |
| 5030 | hjazzi app | ❌ local |
| 5050 | Dashboard | ❌ local |
| 5060 | Upload | ❌ local |
| 5678 | n8n Docker | ❌ local |
| 8000 | Acta Core | ❌ local |
| 8765 | Hermes Gateway | ❌ local |
| 8081 | Ración proxy | ❌ local |

---

## 🛡️ Seguridad

### UFW
⚠️ **INACTIVO** — El firewall está apagado. Si se activa, recordar:
```
ufw allow 22/tcp    # SSH primero
ufw allow 80/tcp
ufw allow 443/tcp
ufw default deny incoming
ufw default allow outgoing
ufw --force enable
```

### SSL
- Let's Encrypt vía Certbot
- Todos los subdominios con HTTPS

### fail2ban
- Verificar si está instalado

---

## 📁 Estructura del Filesystem

### /var/www/ (documentos web)
```
acta.hjazzi.com/    cv.hjazzi.com/       editor.hjazzi.com/
elgallo.hjazzi.com/ estiloyvida.hjazzi.com/ estiloyvida/
evolution.hjazzi.com/ hjazzi/            html/
leadcapture.hjazzi.com/ leadcapture/     logis.hjazzi.com/
logis/              nicolas.hjazzi.com/  nicolas/
paleta.hjazzi.com/  racion.hjazzi.com/   racion/
shangrila.hjazzi.com/ shangrila/         shop-hjazzi/
shop.hjazzi.com/    uropic.hjazzi.com/   uropic/
```

### /opt/ (aplicaciones)
```
acta-core/          containerd/         estiloyvida/
google/             hermes-dashboard/   hermes-upload/
leadcapture/        logis/              n8n/
nicolas/            shop-hjazzi/        uropic/
```

### /root/.hermes/ (corazón del agente)
```
config.yaml         .env                skills/
scripts/            cron/               evolution/
memories/           sessions/           state.db
```

---

## 🧬 Meta Evolution

### Scripts en /root/.hermes/scripts/
- `guardian.py` — Watchdog general (cada 15min)
- `health_monitor.py` — Métricas del VPS
- `health_checker.py` — Verificación rápida
- `auto_watcher.py` — Auto-reparación (cada 5min)
- `memory_core.py` — API de memoria
- `predictor.py` — Tendencias (cada hora)
- `benchmark_suite.py` — 8 tests de calidad
- `daily_digest.py` — Reporte diario
- `post_session.py` — Reflexión post-sesión
- `post_session_reflect.py` — Reflexión extendida
- `project_framework.py` — Framework 9 pasos
- `market_intelligence.py` — Escaneo diario
- `memory_compactor.py` — Purga
- `memory_sanity.py` — Limpieza
- `deep_diagnosis.py` — IA para fallos graves
- `drift_detector.py` — Detecta configs divergentes
- `freshness.py` — Verifica actualidad
- `event_logger.py` — Log centralizado
- `alerter.py` — Notificaciones
- `state_verifier.py` — Verifica STATE.md

### Backups
- `hermes_backup.sh` — Backup de Hermes
- `app_backup.sh` — Backup de apps
- `ecc_backup.py` — Backup Evolution
- `trading_agent_watchdog.sh` — Watchdog trading

---

## 🔄 Cron Jobs

Jobs gestionados por Hermes en `/root/.hermes/cron/jobs.json`.
Para verlos: `hermes cron list` o consultar `cronjob(action='list')`.

---

## 📊 Estado Actual

- **Disco:** 18 GB / 193 GB (9%)
- **RAM:** 2.8 GB / 11 GB (25%)
- **Servicios activos:** ~20
- **Docker:** n8n corriendo
- **UFW:** ❌ INACTIVO

---

> 📝 **Generado:** 2026-07-27 por Hermes Agent
> 🔗 Ver también: [[meta-evolution/arquitectura|Meta Evolution]] · [[recursos/vps|Infraestructura VPS]] · [[recursos/api-keys|API Keys]]
