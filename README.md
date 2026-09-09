# PATI 4Apps — workshop static

~10-slide HTML deck + companion ecosystem diagram for the Thầy Thành / village session.

## Live URLs (GitHub Pages · main/root)

| Asset | URL |
|-------|-----|
| **Deck** | https://tuanquang269.github.io/pati-4apps-workshop/ |
| **Diagram (present)** | https://tuanquang269.github.io/pati-4apps-workshop/ecosystem-workflow.html?present=1 |
| Diagram (embed) | https://tuanquang269.github.io/pati-4apps-workshop/ecosystem-workflow.html?present=1&embed=1 |
| Diagram (file) | https://tuanquang269.github.io/pati-4apps-workshop/ecosystem-workflow.html |

## Local / offline

```bash
cd pati-4apps-workshop
python3 -m http.server 8080
# open http://localhost:8080/
```

- Fonts are **self-hosted** under `assets/fonts/` (Inter, Roboto Condensed, JetBrains Mono). No Google Fonts CDN.
- `ecosystem-workflow.html` JS is fully inline; ambient edge/node trace runs without network when `data-animation="trace"` is set (bundled).
- Prefer `python -m http.server` for local preview. Opening via `file://` usually works for fonts + CSS animation in Chromium; some browsers restrict `localStorage` / iframe quirks on `file://` — if motion or iframe looks stuck, use the local server.
- Deck slide “Toàn cảnh” embeds `ecosystem-workflow.html?present=1&embed=1` (interactive iframe).

## Brand

Black `#0B0D0A` · White `#FFFFFF` · Lime `#9EDB00` · Soft Gray `#F4F5F5`  
Display: Roboto Condensed · Body: Inter  
Line: *Where Humans Direct, AI Delivers*

**Hard lock:** never show store name “Wellness Nest” or domain `wellnessnest.co` in this deck.

Generated for Kevin Kreative / PATI Group. Free public static — no spend.
