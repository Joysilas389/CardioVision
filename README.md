# ❤️ CardioVision — ECG Learning & Analysis App

**By Dr. Silas Joy Agbesi** | Medical Officer, Akim Oda Government Hospital, Ghana 🇬🇭

An interactive web app that teaches ECG interpretation from first principles and provides AI-powered ECG analysis.

## Features
- 🔬 **AI ECG Analysis** — Upload any ECG image for instant structured interpretation via Claude Vision
- 🎓 **12-Lead Tutorial** — 10-step interactive course with SVG diagrams and quizzes
- 📚 **Learn** — Rich curriculum from ecgbook.com (13 chapters, 38 topics)
- 💓 **Rhythm Simulator** — 8 animated ECG rhythms with clinical details
- 📋 **ECG Reference Card** — HD zoomable Del Rosario cheat sheet
- 🛡️ **Safety-First** — Conservative interpretation, emergency escalation language

## Deploy in 2 Minutes (Free)

### Option 1: Netlify (Easiest — Drag & Drop)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `cardiovision-deploy` folder onto the page
3. Done! Your site is live at `https://random-name.netlify.app`
4. Click **Site settings → Change site name** to get `https://cardiovision.netlify.app`

### Option 2: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `cd cardiovision-deploy && vercel`
3. Follow the prompts — done!

### Option 3: GitHub Pages (Best for long-term)
1. Create a new GitHub repo called `cardiovision`
2. Upload all files from this folder to the repo
3. Go to **Settings → Pages → Source: GitHub Actions**
4. The workflow auto-deploys on every push
5. Your site is live at `https://yourusername.github.io/cardiovision`

### Option 4: Any Static Host
This is a single `index.html` file. Upload it to **any** web server:
- Firebase Hosting
- Cloudflare Pages
- Amazon S3 + CloudFront
- DigitalOcean App Platform
- Render.com
- Surge.sh (`npm i -g surge && surge .`)

## How It Works
- Single HTML file — no build step, no Node.js, no dependencies to install
- React 18 + Babel loaded from CDN
- AI analysis calls the Anthropic API directly from the browser
- All ECG content and reference images are embedded in the file

## Tech Stack
- React 18 (CDN)
- Canvas API (animated ECG rhythms)
- SVG (tutorial diagrams)
- Claude Sonnet Vision API (ECG analysis)
- ecgbook.com curriculum

## License
Educational use. Not a medical device. Not FDA/CE approved.

---
*Built with ❤️ in Ghana by Dr. Silas Joy Agbesi*
