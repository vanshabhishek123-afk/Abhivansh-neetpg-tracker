# 🩺 MedTracker Pro – MBBS Study System

## ⚡ Netlify pe Deploy Karne ke Steps

### Step 1 – Prerequisites
- Node.js install hona chahiye: https://nodejs.org (LTS version download karo)
- Netlify account: https://netlify.com (free hai)

### Step 2 – Project Setup (ek baar)
```bash
# ZIP extract karne ke baad folder mein jaao
cd mbbs-tracker

# Dependencies install karo
npm install

# Build karo
npm run build
```

### Step 3 – Netlify Deploy (2 ways)

#### Option A: Drag & Drop (Sabse Easy) ✅
1. `npm run build` chalaao → `dist/` folder ban jaayega
2. Netlify.com pe jaao → Login karo
3. "Sites" page pe jaao
4. `dist` folder ko **drag & drop** karo Netlify ke "Deploy" area mein
5. 30 seconds mein app live! 🎉

#### Option B: Netlify CLI
```bash
npm install -g netlify-cli
netlify deploy --prod --dir=dist
```

---

## 🔧 Local Development
```bash
npm run dev
# Browser mein jaao: http://localhost:5173
```

---

## 📱 App Features
- **Daily Log**: 00:00–23:00 hourly activity tracking
- **QBank**: Subject/topic-wise question tracking + screenshot AI analysis
- **Reports**: Daily / Weekly / Monthly AI-generated reports
- **Settings**: API key, 19-subject accuracy tracker

## ⚠️ Important Notes
- App ka data browser localStorage mein save hota hai
- AI features kaam karte hain as-is (Claude AI built-in)
- Mobile pe bhi kaam karta hai perfectly
