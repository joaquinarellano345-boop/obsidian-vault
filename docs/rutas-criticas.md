---
tags: [vps, rutas, referencia]
created: 2026-07-27
---

# 📁 Rutas Críticas del VPS

## Si hay que reconstruir todo, empezar por acá

### Nginx
- **Sites:** `/etc/nginx/sites-enabled/`
- **SSL:** `/etc/letsencrypt/live/`
- **Logs:** `/var/log/nginx/`

### Hermes Agent
- **Config:** `/root/.hermes/config.yaml`
- **Env:** `/root/.hermes/.env`
- **Skills:** `/root/.hermes/skills/`
- **Memories:** `/root/.hermes/memories/`
- **Scripts:** `/root/.hermes/scripts/`
- **Cron jobs:** `/root/.hermes/cron/jobs.json`
- **State DB:** `/root/.hermes/state.db`
- **Sessions:** `/root/.hermes/sessions/`

### Meta Evolution
- **Metrics:** `/root/.hermes/evolution/metrics/`
- **Memory:** `/root/.hermes/evolution/memory/`
- **Knowledge:** `/root/.hermes/evolution/knowledge/`
- **Market:** `/root/.hermes/evolution/market/`
- **State:** `/root/.hermes/STATE.md`

### Tiendas (apps)
- **Código:** `/opt/<nombre>/`
- **Web root:** `/var/www/<nombre>.hjazzi.com/` o `/var/www/<nombre>/`

### n8n
- **Docker:** `/opt/n8n/`
- **Acceso:** n8n.hjazzi.com (→ 127.0.0.1:5678)
- **Admin:** admin@hjazzi.com

### Backups
- **Scripts:** `/root/.hermes/scripts/*backup*`
- **Evolution:** `/root/.hermes/evolution/backups/`

---

> 📝 [[docs/manual-vps|← Manual VPS]]
