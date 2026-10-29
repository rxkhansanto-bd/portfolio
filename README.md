# Shanto Portfolio — Next.js

বাংলা Hind Siliguri ফন্টে তৈরি responsive portfolio website।

## Local run

1. Node.js LTS ইনস্টল করুন: https://nodejs.org/
2. ZIP extract করে project folder-এ Terminal / PowerShell খুলুন।
3. চালান:

```bash
npm install
npm run dev
```

4. ব্রাউজারে খুলুন: http://localhost:3000

Production build যাচাই করতে:

```bash
npm run build
```

## নিজের তথ্য পরিবর্তন

`app/page.tsx` ফাইলে নিচের জায়গাগুলো এডিট করুন:

- `শান্ত মিয়া` / `Shanto Miah` — নাম
- `your.email@example.com` — নিজের ইমেইল (দুই জায়গায়)
- GitHub ও LinkedIn URL — নিজের প্রোফাইল লিংক
- `projects` array — প্রজেক্টের নাম, বিবরণ ও টেকনোলজি
- About section — নিজের পরিচিতি ও স্কিল

## GitHub-এ আপলোড

GitHub-এ একটি **New repository** তৈরি করুন। তারপর project folder-এর terminal-এ:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

`YOUR-USERNAME` ও `YOUR-REPOSITORY` নিজের GitHub তথ্য দিয়ে বদলাবেন।

## Vercel deploy

1. https://vercel.com এ GitHub দিয়ে sign in করুন।
2. **Add New → Project** চাপুন।
3. আপনার portfolio repository Import করুন।
4. Framework Preset `Next.js` থাকলে সেটিই রাখুন; Build/Output settings ডিফল্ট রাখুন।
5. **Deploy** চাপুন।

পরবর্তীতে GitHub-এর `main` branch-এ push করলে Vercel সাধারণত স্বয়ংক্রিয়ভাবে নতুন deployment করবে।

## Font note

Hind Siliguri ফন্ট `next/font/google` দিয়ে লোড হয়। Build-এর সময় Google Fonts-এ নেটওয়ার্ক অ্যাক্সেস প্রয়োজন।
