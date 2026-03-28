# 🔷 FlowBuilder — Visual Workflow & Container Builder

The most powerful open-source visual workflow constructor with built-in AI assistant. Build, connect, and deploy complex automations without writing code.

![FlowBuilder](https://img.shields.io/badge/version-1.0.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Blocks](https://img.shields.io/badge/blocks-100%2B-orange)

## ✨ Features

### 🎨 Visual Canvas Editor
- Infinite canvas with pan & zoom
- Drag & drop blocks from 15+ categories
- Bezier curve connections with animated flow
- Multi-select, copy/paste, undo/redo
- Grid snapping and alignment
- Mini-map navigation

### 🤖 AI Assistant (No API Key Required!)
- Built-in AI that understands natural language
- "Read emails and save attachments to S3" → auto-creates workflow
- Smart block suggestions based on context
- Uses free Hugging Face Inference API + local fallback

### 📦 100+ Blocks in 15 Categories

| Category | Blocks |
|----------|--------|
| 🤖 AI & ML | Text Generation, Image Gen, STT, TTS, Sentiment, Translation, OCR... |
| 📊 Data | DB Query, CSV Import, JSON Transform, Filter, Sort, Merge, Validate... |
| 🌐 API & Web | HTTP Request, REST, GraphQL, WebSocket, Webhook, Gateway... |
| 💬 Messaging | Email, Slack, Telegram, Discord, WhatsApp, SMS, Push... |
| ⚙️ DevOps | Docker Build/Run, K8s, CI/CD, Git, Shell, SSH, Health Check... |
| ☁️ Cloud | AWS S3/Lambda, Azure, GCP, Firebase, Cloudflare, Vercel... |
| 🗄️ Database | PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, DynamoDB... |
| 🔀 Logic | If/Else, Switch, Loop, Parallel, Delay, Retry, Error Handler... |
| 🔧 Transform | JS Function, Python, Regex, Template, Markdown→HTML, PDF... |
| 📈 Analytics | Google Analytics, Charts, Reports, Dashboards, A/B Test... |
| 🔐 Security | OAuth2, JWT, Encryption, CAPTCHA, Rate Limit, CORS... |
| 💾 Storage | File R/W, FTP, Cloud Sync, Zip, Backup, Archive... |
| 📱 Social | Twitter, Instagram, LinkedIn, YouTube, TikTok, Reddit... |
| 💳 Payment | Stripe, PayPal, Invoices, Subscriptions, Refunds... |
| 🏢 CRM | Salesforce, HubSpot, Zendesk, Jira, Notion, Airtable... |

### ⌨️ Keyboard Shortcuts
- `Ctrl+K` — Command palette / block search
- `Ctrl+Z/Y` — Undo / Redo
- `Ctrl+C/V` — Copy / Paste blocks
- `Delete` — Remove selected
- `Space+Drag` — Pan canvas
- `Scroll` — Zoom in/out
- `Shift+Click` — Multi-select

## 🚀 Quick Start

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/flow-builder.git
cd flow-builder
```

2. Open `index.html` in your browser. That's it! No build step, no dependencies.

```bash
open index.html
# or
python -m http.server 8000
```

3. Start building workflows by dragging blocks from the left panel!

## 🏗️ Architecture

Single-file application — everything is in `index.html`:
- Pure HTML5, CSS3, JavaScript (ES6+)
- Canvas-based rendering for connections
- Zero external dependencies
- LocalStorage for persistence
- Export/Import as JSON

## 📄 License

MIT — use it however you want.

## 🌟 Star this repo if you find it useful!