# Golden Bake House — The Sweet Story

Premium bakery website for **Golden Bake House, Sathupally**  
`Baked With Love Since 1998`

## Run locally in VS Code (2 options)

### Option 1 — Double click (simplest)
1. Download / copy the folder `golden-bake-house` to your computer
2. Double-click `index.html` → it opens in your browser. Done.

### Option 2 — VS Code Live Server (recommended)
1. Open VS Code → `File` → `Open Folder` → select `golden-bake-house`
2. Install extension **Live Server** (by Ritwick Dey) if not installed
3. Right-click `index.html` → **Open with Live Server**
4. Site runs at http://127.0.0.1:5500

> No build step, no npm, no terminal needed. Internet required on first load for Google Fonts & Tailwind CDN (after that it's cached).

## Files
- `index.html` — entire website (self-contained, ~800 lines)
- `README.md` — this file

## Customizing
- Search for `092929 88177` to change phone
- Search for `RTC Bus Stand` to change address
- Product list is in `const products = [...]` near line ~320 — edit name/price/image there
- Colors are in `tailwind.config` at the top — change hex values

## Deploy
Drag the folder to Netlify / Vercel, or push to GitHub Pages — works instantly.

Need a split version with separate `style.css` + `script.js` or offline fonts? Just ask.
