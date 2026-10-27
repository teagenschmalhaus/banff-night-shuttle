# Banff Night Shuttle

Static site for [banffnightshuttle.com](https://banffnightshuttle.com): private, flat-rate YYC ↔ Banff shuttle, late-night focus. Plain HTML/CSS/JS, no build step. Hosted on Cloudflare Pages.

## Pages
- `index.html` — YYC → Banff (hero, pricing, booking form, FAQ, contact)
- `banff-to-yyc.html` — reverse direction
- `canmore-shuttle.html` — Canmore stop
- `blog/` — SEO articles

## Before launch — replace placeholders
| Placeholder | Where | What |
|---|---|---|
| `YOUR_WEB3FORMS_ACCESS_KEY` | all booking pages | New Web3Forms key for the Banff inbox |
| `AW-XXXXXXXXXX` | all pages `<head>` | Google Ads tag ID |
| `AW-XXXXXXXXXX/XXXXXXXXXXXX` | `js/main.js` | Ads conversion `send_to` |
| `G-XXXXXXXXXX` | all pages `<head>` | Google Analytics ID |
| CSS hero (`css/style.css` `.hero`) | | Swap for a Banff night photo |

Find them all: `grep -rn "XXXXXXXXXX\|YOUR_WEB3FORMS" .`
