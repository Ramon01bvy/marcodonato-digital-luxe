# Marcodonato Digital Luxe B.V.

Exclusieve Next.js website met luxe design, animated gradient, gouden glow effecten en professioneel contactformulier.

## 🚀 Lokaal draaien

1. Pak de repository uit of clone je repo.
2. Installeer dependencies
```bash
npm install
```
3. Start de development server
```bash
npm run dev
```

Open daarna [http://localhost:3000](http://localhost:3000).

## 🌐 Deploy naar GitHub Pages (met Actions)

Deze repo bevat een workflow: `.github/workflows/deploy.yml`

Elke keer dat je naar **main** pusht:
- GitHub Actions bouwt de site met `npm run build && npm run export`.
- Het resultaat (`out/` map) wordt automatisch gepubliceerd naar de branch **gh-pages**.
- GitHub Pages serveert die branch.

### Instellen op GitHub

1. Ga naar je repo → **Settings → Pages**  
2. Kies:
   - Source: **Deploy from branch**
   - Branch: `gh-pages` → `/ (root)`
3. Klik **Save**

Binnen 1–2 minuten is je site live op:

```
https://<jouw-gebruikersnaam>.github.io/<repo-naam>/
```

## 📂 Project structuur

- `pages/` → Pagina’s en componenten
- `public/` → Logo, afbeeldingen
- `styles/globals.css` → Tailwind + animated gradient
- `.github/workflows/deploy.yml` → GitHub Actions workflow
- `package.json` → Project configuratie

## ✨ Credits

- Ontwikkeld voor **Marcodonato Digital Luxe B.V.**
- Contact: infomarcodonato@protonmail.com
