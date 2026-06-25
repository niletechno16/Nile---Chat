# EzyConnect 🚀
**Connect. Chat. Resolve.**

A modern customer support chat platform UI built with pure HTML/CSS/JS.

## Pages
- 💬 **Chats** — Live conversations with AI suggestions
- 🤖 **AI Assistant** — Smart reply drafting & summaries  
- 👤 **Contacts** — Customer directory
- 📄 **Templates** — Quick response templates
- 📊 **Analytics** — Performance metrics & charts
- ⚙️ **Settings** — Profile, notifications, AI config

## Deploy to fly.io

### 1. Install flyctl
```bash
curl -L https://fly.io/install.sh | sh
```

### 2. Login
```bash
fly auth login
```

### 3. Launch (first time)
```bash
fly launch --name ezyconnect --region iad --yes
```

### 4. Deploy
```bash
fly deploy
```

### 5. Open
```bash
fly open
```

Your app will be live at: `https://ezyconnect.fly.dev`

## Local preview
Just open `index.html` in your browser — no server needed!
