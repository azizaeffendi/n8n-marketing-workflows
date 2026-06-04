# Setup n8n — Panduan Lengkap

## Instalasi n8n

### Opsi 1: npm (Development/Testing)
```bash
npm install n8n -g
n8n start
# Buka: http://localhost:5678
```

### Opsi 2: Docker (Recommended)
```bash
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  -e N8N_BASIC_AUTH_ACTIVE=true \
  -e N8N_BASIC_AUTH_USER=admin \
  -e N8N_BASIC_AUTH_PASSWORD=yourpassword \
  n8nio/n8n
```

### Opsi 3: Docker Compose (Production)
```yaml
version: '3.8'
services:
  n8n:
    image: n8nio/n8n
    restart: always
    ports:
      - "5678:5678"
    environment:
      - N8N_BASIC_AUTH_ACTIVE=true
      - N8N_BASIC_AUTH_USER=admin
      - N8N_BASIC_AUTH_PASSWORD=${N8N_PASSWORD}
      - N8N_HOST=${N8N_HOST}
      - N8N_PROTOCOL=https
      - WEBHOOK_URL=https://${N8N_HOST}/
      - GENERIC_TIMEZONE=Asia/Jakarta
    volumes:
      - n8n_data:/home/node/.n8n
volumes:
  n8n_data:
```

### Opsi 4: Railway (1-Click Deploy)
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app)
1. Klik tombol di atas
2. Set environment variables
3. Deploy otomatis

---

## Import Workflow

1. Buka n8n di browser
2. Klik **New Workflow** atau **+**
3. Klik ikon **⋮** (tiga titik) di pojok kanan atas
4. Pilih **Import from File**
5. Pilih file `.json` dari folder `workflows/`
6. Klik **Save** dan konfigurasi credentials

---

## Setup Credentials Umum

### OpenAI
1. Buka [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
2. Create new key
3. Di n8n: Settings → Credentials → Add → OpenAI → paste key

### Google Analytics 4
1. Buka Google Cloud Console
2. Enable Google Analytics Data API
3. Buat Service Account + download JSON key
4. Di n8n: Add credential → Google Analytics OAuth2

### Meta Ads
1. Buka [developers.facebook.com](https://developers.facebook.com)
2. Create App → Marketing API
3. Generate Access Token
4. Di n8n: Add credential → Facebook Graph API

### Airtable
1. Buka [airtable.com/create/tokens](https://airtable.com/create/tokens)
2. Create Personal Access Token
3. Di n8n: Add credential → Airtable Token

### Slack
1. Buka [api.slack.com/apps](https://api.slack.com/apps)
2. Create New App → dari Scratch
3. Add Bot Token Scopes: `chat:write`, `channels:read`
4. Install ke workspace, copy Bot Token
5. Di n8n: Add credential → Slack

---

## Tips Production

- **Backup workflow** secara berkala: Settings → Export All
- **Monitor execution** di menu Executions — lihat error dan timing
- **Rate limiting** — beberapa API ada limit, set delay antar request
- **Error handling** — tambahkan Error Trigger workflow untuk notifikasi jika ada yang gagal