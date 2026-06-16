# 🍦 The Great Syrup Showdown

An animated, interactive ranking of **33 tested flavours** from a soft‑serve / slushie flavour‑tasting session. Scores are the corrected one‑decimal average of three tasters (K, C, and A).

**▶ Live page:** https://claudechopper.github.io/syrup-showdown/

## What's inside
- **Winner podium** — top 3, with hover fireworks 🎆 and dancing fruit mascots
- **Animated flavour race** — bars fill to each corrected average score
- **Filter & sort** — Keepers / Retest / Cuts, by score or A→Z
- **Spotlight panel** — click any flavour for its verdict and tasting note
- **33 flavour cards** with photos and a practical menu recommendation each

It's a single self‑contained `index.html` (vanilla HTML/CSS/JS — no build step, no dependencies) plus 33 photos in `assets/flavours/`.

## Run locally
Open it directly:
```bash
open index.html
```
…or serve it, so lazy‑loaded images behave exactly like the live site:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## The verdicts
| Tag | Meaning |
|---|---|
| 🟢 **Keep** | Clear winners — shortlist for the menu |
| 🟠 **Retest** | Mid‑pack — worth a customer test before deciding |
| 🔴 **Cut** | Weak in this tasting — drop unless demand says otherwise |

🥇 **Banana** takes it with a **9.7/10** average, ahead of 🥈 Peach (9.0) and 🥉 Creme De Menthe (8.8).

## Notes from the tasting
- The original sheet appeared to truncate some overall scores; this report uses normal one‑decimal averages.
- Pairings flagged for a small‑batch test: **blueberry + lemon**, and **creme de menthe + chocolate syrup**.
- Ops note: 1.5 oz syrup per 16 oz base.

---
<sub>Static site, hosted on GitHub Pages. No tracking, no dependencies.</sub>
