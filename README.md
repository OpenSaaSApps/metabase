# metabase

> Click To Deploy Metabase — Open Source Business Intelligence & Analytics

[![Sync](https://github.com/opensaasapps/metabase/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/metabase/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/metabase/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/metabase/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/metabase)](https://hub.docker.com/r/thefractionalpm/metabase)

Upstream: [metabase/metabase](https://github.com/metabase/metabase) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `MB_DB_TYPE` | ⚪ | |
| `MB_DB_HOST` | ⚪ | |
| `MB_DB_PORT` | ⚪ | |
| `MB_DB_DBNAME` | ⚪ | |
| `MB_DB_USER` | ⚪ | |
| `MB_DB_PASS` | ✅ | |
| `MB_EMAIL_SMTP_HOST` | ✅ | |
| `MB_EMAIL_SMTP_PORT` | ⚪ | |
| `MB_EMAIL_SMTP_SECURITY` | ⚪ | |
| `MB_EMAIL_SMTP_USERNAME` | ✅ | |
| `MB_EMAIL_SMTP_PASSWORD` | ✅ | |
| `MB_EMAIL_FROM_ADDRESS` | ⚪ | |

## Image

```
docker pull metabase/metabase:latest
docker pull thefractionalpm/metabase:latest
```

## Ports

| Port | Service |
|---|---|
| `3000` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
