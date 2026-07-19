# Kinza Naseer — Pakistani Showbiz News Website

Static website (HTML/CSS/JS only — no build step needed).

## Kaise Use Karein
1. Zip file extract karein.
2. `index.html` ko kisi bhi browser mein double-click karke khol lein — poori site chal jayegi.
3. Online daalne ke liye kisi bhi free/cheap hosting par upload kar sakti hain: Netlify, Vercel, GitHub Pages, ya kisi bhi cPanel hosting (Hostinger, GoDaddy waghera). Bas poora folder upload kar dein.
4. Apna domain (jaise kinzanaseer.com) us hosting se connect kar dein.

## Pages
- `index.html` — Home page
- `celebrity-news.html` — Celebrity / Actress news listing
- `drama-reviews.html` — Drama reviews listing
- `trending.html` — Trending / heat-ranked stories
- `about.html` — About Kinza Naseer
- `contact.html` — Contact form
- `article.html` — Sample full article template (copy this file to add new stories)

## Content Update Karna
- Har page ek plain HTML file hai — Notepad, VS Code, ya kisi bhi text editor se khol kar seedha text/Urdu content change kar sakti hain.
- Naya story add karne ke liye `article.html` copy karke naam change karein (e.g. `article-2.html`) aur andar ka content update kar dein, phir home/listing page par uska link laga dein.
- Card mein "TRP %" number story ki trending strength dikhata hai — chahen to har story ke hisaab se number badal sakti hain.

## Design
- Fonts: Anton (bold English headlines), Noto Nastaliq Urdu (Urdu text), Poppins (body/UI) — Google Fonts se load hote hain, isliye internet connection chahiye.
- Colors: near-black background + rose-red aur marigold-gold accents — "breaking news tabloid" look ke liye.
- Fully responsive — mobile, tablet, desktop sab par kaam karta hai.
