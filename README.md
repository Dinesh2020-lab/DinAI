# Dinai 🤖
A clean AI chat app powered by **Grok AI (xAI)** — built with pure HTML, CSS & JS. No frameworks, no build step, single file.

## ✨ Features
- Sign up / Login with localStorage persistence
- Powered by **Grok-3-mini** (OpenAI-compatible API)
- **$25 free credits/month** — no quota issues
- Full conversation memory
- Auto dark mode
- Mobile responsive

## 🔑 Get Your FREE Grok API Key
1. Go to [console.x.ai](https://console.x.ai)
2. Sign up with your X (Twitter) account
3. Go to **API Keys** → **Create API Key**
4. Copy the key (starts with `xai-...`)
5. Paste it during Dinai sign-up

## 🚀 Deploy on GitHub Pages (Free Hosting)

### Step 1 — Create GitHub repo
1. Go to [github.com](https://github.com) → **New repository**
2. Name: `dinai` → **Public** → **Create repository**

### Step 2 — Upload files
1. Click **Add file → Upload files**
2. Upload `index.html` and `README.md`
3. Click **Commit changes**

### Step 3 — Enable Pages
1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` | Folder: `/ (root)` → **Save**
4. Live in ~60 seconds at:
```
https://YOUR_USERNAME.github.io/dinai
```

## 💻 Run Locally
```bash
# Just open in browser — no server needed
open index.html

# Or use a local server
npx serve .
```

## 📁 Structure
```
dinai/
├── index.html   ← entire app
└── README.md
```

## ⚠️ Notes
- Accounts saved in browser localStorage
- API keys stored locally — use on personal devices only
- For multi-device support, use Firebase or Supabase backend
