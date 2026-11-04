# Guaros Vet · Suite Digital

Internal marketing suite for **Guaros Vet** (Barquisimeto, Lara). It guides the 14‑day launch of the *Plan de Salud Preventiva* and collects every brand resource in one place.

## Sections
- **Fase 3 · Cierre (días 9–14):** cohort seat counter, a personalized WhatsApp follow-up script (copy it or open it in WhatsApp), quick replies to objections, and scarcity, last-call and thank-you posts.
- **Fase 2 · Anuncio (días 5–8):** a 5-slide launch carousel preview with Canva notes and a caption, the QUO alliance Reel script, FAQ and social proof.
- **Stories (14 días):** a day-by-day 9:16 Story generator. You can edit the copy, change the background, copy the text and mark each Story as published.
- **Planes:** an editable plan catalog with a QUO installment calculator (bi-weekly payments). Each plan sheet can be copied or sent by WhatsApp.
- **Banco Marca & Canva:** the clean logo, a palette you can copy and test live, the fonts, the bubble pattern, contact details and a gallery of Canva pieces you can download.

Edits such as seat counts, prices, Story text and palette tests are saved in the browser (`localStorage`).

## Tech
A static HTML page (`public/index.html`) that uses Tailwind CSS (CDN), Font Awesome and Google Fonts (Fredoka + Inter). Images are served through the Netlify Image CDN. There is no build step.

## Run locally
```bash
netlify dev
# or any static server
npx serve public
```
The Image CDN URLs (`/.netlify/images`) need `netlify dev` or a deployed site.
