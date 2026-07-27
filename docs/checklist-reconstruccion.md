---
tags: [vps, backup, emergencia]
created: 2026-07-27
---

# 🚨 Checklist de Reconstrucción

Si el VPS muere y hay que levantar todo de cero:

## 1. Contratar VPS
- [ ] Contabo VPS (o similar)
- [ ] Ubuntu 24.04
- [ ] Mínimo 4 GB RAM, 50 GB disco
- [ ] Apuntar DNS de hjazzi.com a la nueva IP

## 2. Instalar base
- [ ] `apt update && apt upgrade`
- [ ] nginx, certbot, python3, git, docker
- [ ] Node.js (para n8n y algunas apps)

## 3. Recuperar Hermes
- [ ] Instalar Hermes Agent (`curl -fsSL https://get.hermes-agent.com | bash`)
- [ ] Restaurar `/root/.hermes/config.yaml` y `/root/.hermes/.env`
- [ ] Restaurar `/root/.hermes/skills/`
- [ ] Restaurar `/root/.hermes/memories/`
- [ ] Restaurar `/root/.hermes/scripts/`

## 4. Recuperar apps
- [ ] Clonar cada repo de /opt/
- [ ] Recrear venvs: `python3 -m venv venv && pip install -r requirements.txt`
- [ ] Copiar archivos .env de cada app
- [ ] Crear servicios systemd para cada una

## 5. Recuperar nginx
- [ ] Copiar configs de `/etc/nginx/sites-enabled/`
- [ ] `nginx -t && systemctl restart nginx`
- [ ] `certbot --nginx` para cada subdominio

## 6. n8n
- [ ] `docker compose up -d` en /opt/n8n/
- [ ] Restaurar backup de workflows

## 7. Meta Evolution
- [ ] Restaurar cron jobs desde `/root/.hermes/cron/jobs.json`
- [ ] Verificar scripts en `/root/.hermes/scripts/`
- [ ] Restaurar `/root/.hermes/evolution/`

## 8. Verificar
- [ ] Todos los subdominios responden
- [ ] `hermes-dashboard` (5050)
- [ ] `hermes-gateway` (8765)
- [ ] Tiendas: uropic, shangrila, estiloyvida, etc.
- [ ] n8n.hjazzi.com
- [ ] evolution.hjazzi.com

---

> 📝 [[docs/manual-vps|← Manual VPS]] · [[docs/rutas-criticas|Rutas Críticas]]
