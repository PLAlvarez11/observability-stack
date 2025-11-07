# Runbook — Operaciones en Producción

## Monitoreo
- **Grafana**: http://<vps>:13000
- **Prometheus**: http://<vps>:19090

## Recuperación
- Reiniciar replicador:
  ```bash
  cd /srv/etl-stack && docker compose restart replicator
