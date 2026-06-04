<div align="center">

# ⚡ n8n Marketing Workflows

**30+ workflow otomasi marketing siap pakai — import & jalankan dalam menit**

[![n8n](https://img.shields.io/badge/n8n-compatible-orange?style=for-the-badge&logo=n8n)](https://n8n.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Workflows](https://img.shields.io/badge/Workflows-30+-brightgreen?style=for-the-badge)](workflows/)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-blue?style=for-the-badge)](CONTRIBUTING.md)
[![Made in Indonesia](https://img.shields.io/badge/Made%20in-Indonesia-red?style=for-the-badge)](https://github.com/azizaeffendi)

<br/>

> **Stop setup otomasi dari nol. Import workflow yang sudah terbukti bekerja — hemat puluhan jam development dan langsung jalankan dalam menit.**

```
┌────────────────────────────────────────────────────────────────┐
│                    MARKETING AUTOMATION HUB                    │
├─────────────────┬──────────────────┬───────────────────────────┤
│  📧 Email       │  📱 Social Media │  👥 CRM & Leads           │
│  Welcome seq    │  Auto-publish    │  Lead scoring             │
│  Follow-up      │  Content cal     │  Contact sync             │
│  Re-engagement  │  Cross-post      │  Pipeline update          │
├─────────────────┼──────────────────┼───────────────────────────┤
│  📊 Analytics   │  🤖 AI-Powered   │  🛒 E-Commerce            │
│  Weekly reports │  AI copywriting  │  Abandoned cart           │
│  KPI alerts     │  Auto-summary    │  Order notifications      │
│  Data sync      │  Content ideas   │  Review requests          │
└─────────────────┴──────────────────┴───────────────────────────┘
```

[📂 Browse Workflows](#-daftar-workflow) · [🚀 Quick Start](#-quick-start) · [🤝 Kontribusi](CONTRIBUTING.md)

</div>

---

## 🌟 Mengapa n8n?

| Fitur | n8n | Zapier | Make (Integromat) |
|-------|-----|--------|-------------------|
| Self-hosted | ✅ | ❌ | ❌ |
| Biaya | Gratis (self-host) | $19-69/bulan | $9-29/bulan |
| Custom code | ✅ JavaScript/Python | ❌ | Terbatas |
| Unlimited executions | ✅ | ❌ (task limit) | ❌ (ops limit) |
| Open source | ✅ | ❌ | ❌ |
| AI integration | ✅ native | Terbatas | Terbatas |

---

## 📂 Daftar Workflow

### 📧 Email Marketing (8 Workflows)
| Workflow | Deskripsi | Integrasi |
|----------|-----------|-----------|
| `welcome-sequence` | Sequence 5 email otomatis untuk subscriber baru | Mailchimp/SendGrid + Webhook |
| `abandoned-cart-recovery` | 3 email recovery untuk cart yang ditinggalkan | WooCommerce + Brevo |
| `re-engagement-campaign` | Reaktivasi subscriber yang tidak aktif 60+ hari | Mailchimp + Filter |
| `weekly-newsletter-builder` | Kumpul konten → buat draft → kirim newsletter | RSS + OpenAI + Mailchimp |
| `email-list-cleaner` | Cek dan hapus email bounced/unsubscribed secara berkala | Mailchimp + Google Sheets |
| `birthday-email-automation` | Kirim email ucapan ulang tahun ke kontak CRM | Airtable + SendGrid |
| `post-purchase-sequence` | Follow-up setelah pembelian: review, upsell, loyalty | Shopify + Klaviyo |
| `lead-magnet-delivery` | Kirim otomatis lead magnet setelah opt-in | Typeform + Gmail |

### 📱 Social Media (7 Workflows)
| Workflow | Deskripsi | Integrasi |
|----------|-----------|-----------|
| `content-calendar-publisher` | Jadwalkan & publish konten dari Google Sheets ke semua platform | Google Sheets + Instagram + LinkedIn |
| `cross-platform-reposter` | Auto-repost konten Instagram ke Facebook & LinkedIn | Instagram + Facebook + LinkedIn |
| `viral-content-alert` | Monitor dan notifikasi konten viral di niche Anda | Twitter API + Slack |
| `competitor-monitor` | Track postingan kompetitor dan dapatkan notifikasi | RSS + Telegram |
| `ugc-collector` | Kumpulkan UGC (user generated content) yang mention brand | Twitter + Instagram + Airtable |
| `tiktok-idea-generator` | Generate ide konten TikTok mingguan dengan AI | OpenAI + Notion |
| `social-media-analytics-report` | Laporan mingguan performa semua platform ke email | Meta API + Google Analytics + Gmail |

### 👥 CRM & Lead Management (6 Workflows)
| Workflow | Deskripsi | Integrasi |
|----------|-----------|-----------|
| `lead-scoring-automation` | Skor lead otomatis berdasarkan behaviour dan interaksi | HubSpot + Webhook |
| `lead-form-to-crm` | Form submission langsung ke CRM + notifikasi sales | Typeform + HubSpot + Slack |
| `contact-enrichment` | Lengkapi data kontak otomatis dari LinkedIn/Clearbit | Clearbit + HubSpot |
| `deal-pipeline-automation` | Update stage pipeline berdasarkan trigger tertentu | HubSpot + Slack |
| `whatsapp-lead-capture` | Tangkap lead dari WhatsApp ke CRM | WhatsApp API + Airtable |
| `meeting-follow-up` | Kirim follow-up otomatis setelah meeting via Calendly | Calendly + Gmail + HubSpot |

### 📊 Analytics & Reporting (5 Workflows)
| Workflow | Deskripsi | Integrasi |
|----------|-----------|-----------|
| `weekly-kpi-report` | Kompilasi KPI mingguan dan kirim ke Slack/email | Google Analytics + Meta Ads + Slack |
| `ad-spend-alert` | Notifikasi jika spend iklan melebihi threshold | Google Ads + Meta Ads + Telegram |
| `google-analytics-to-sheets` | Sync data GA4 harian ke Google Sheets | Google Analytics + Google Sheets |
| `revenue-dashboard-update` | Update dashboard revenue dari berbagai sumber | Stripe + Shopify + Google Sheets |
| `competitor-price-tracker` | Monitor harga kompetitor dan catat di spreadsheet | Web Scraper + Google Sheets |

### 🤖 AI-Powered (4 Workflows)
| Workflow | Deskripsi | Integrasi |
|----------|-----------|-----------|
| `ai-content-ideation` | Generate 10 ide konten mingguan berdasarkan niche dan tren | OpenAI + Notion + Slack |
| `ai-blog-writer` | Dari keyword → outline → draft artikel lengkap | OpenAI + WordPress |
| `ai-ad-copy-generator` | Generate variasi copy iklan untuk A/B testing | OpenAI + Google Sheets |
| `customer-feedback-analyzer` | Analisis sentimen ulasan pelanggan dengan AI | OpenAI + Google Sheets + Slack |

---

## 🚀 Quick Start

### 1. Install n8n

```bash
# Via npm (paling mudah)
npm install n8n -g
n8n start

# Via Docker (recommended untuk production)
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
```

Buka browser: `http://localhost:5678`

### 2. Import Workflow

1. Di n8n, klik **+** untuk tambah workflow baru
2. Klik **⋮** (tiga titik) → **Import from File**
3. Pilih file `.json` dari folder `workflows/` repo ini
4. Klik **Import**

### 3. Konfigurasi Credentials

Setiap workflow butuh credentials yang berbeda. Lihat [CREDENTIALS.md](docs/CREDENTIALS.md) untuk panduan setup masing-masing service.

### 4. Aktifkan Workflow

Toggle switch ke **Active** dan workflow siap berjalan!

---

## 📁 Struktur Folder

```
n8n-marketing-workflows/
├── workflows/
│   ├── email-marketing/          # Workflow email
│   ├── social-media/             # Workflow social media
│   ├── crm-leads/                # Workflow CRM & leads
│   ├── analytics-reporting/      # Workflow analytics
│   └── ai-powered/               # Workflow berbasis AI
├── docs/
│   ├── SETUP.md                  # Panduan setup n8n
│   ├── CREDENTIALS.md            # Setup credentials per service
│   └── CUSTOMIZATION.md          # Cara kustomisasi workflow
├── templates/                    # Template sub-workflow yang bisa dipakai ulang
├── CONTRIBUTING.md
└── README.md
```

---

## 💡 Cara Kustomisasi

Setiap workflow bisa dikustomisasi tanpa coding:

1. **Ubah trigger** — webhook, schedule, atau event-based
2. **Tambah filter** — kondisi kapan workflow jalan
3. **Ganti service** — semua node bisa diganti ke service lain
4. **Tambah step** — drag & drop node baru
5. **Gabungkan workflow** — panggil workflow lain sebagai sub-workflow

---

## 🤝 Kontribusi

Punya workflow yang berguna? Share ke komunitas! Lihat [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📜 Lisensi

MIT © [azizaeffendi](https://github.com/azizaeffendi)

---

<div align="center">

**Muhammad Aziz A Effendi**
*Full-Stack Developer · AI Marketing Engineer · Indonesia*

[![GitHub](https://img.shields.io/badge/GitHub-@azizaeffendi-181717?style=flat-square&logo=github)](https://github.com/azizaeffendi)

Berikan ⭐ jika workflow ini menghemat waktu Anda!

</div>