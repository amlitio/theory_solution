# BlogForge — Council of Kings

4 specialist AI agents that turn any question into a verified, SEO-optimised blog post.

| Agent | Role |
|-------|------|
| ✍ REX SCRIPTOR | Writes the full first draft |
| 🔭 REX EXPLORATOR | Identifies authoritative sources & research |
| ⚖ REX VERITAS | Fact-checks every claim |
| 👑 REX CURATOR | Produces the final SEO-optimised post |

---

## Deploy to Vercel (5 minutes)

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "Initial BlogForge"
git remote add origin https://github.com/YOUR_USERNAME/blogforge.git
git push -u origin main
```

### 2. Import to Vercel
- Go to [vercel.com](https://vercel.com) → **Add New Project**
- Import your GitHub repo
- Framework: **Next.js** (auto-detected)

### 3. Add Environment Variable
In Vercel project settings → **Environment Variables**:
```
ANTHROPIC_API_KEY = sk-ant-your-key-here
```
Get your key at [console.anthropic.com](https://console.anthropic.com)

### 4. Deploy
Click **Deploy** — live in ~60 seconds.

---

## Run Locally

```bash
npm install
cp .env.example .env.local
# edit .env.local and add your ANTHROPIC_API_KEY
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)
