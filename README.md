# 🏁 36-0: NASCAR Cup Draft

> **Draft 6 NASCAR legends across 6 eras and try to win every race in a 36-race Cup season.**
> 96 legends. 6 eras. 36 races. 1 goal: 36-0.

A 1-day HTML MVP sports-draft game, in the lineage of:
- 🏆 [**38-0 Football Squad Draft**](https://github.com/TeapoyY/squad-draft-football) — NFL X-0 (2026-07-30)
- 🏎️ [**F1 24-0**](https://github.com/TeapoyY/squad-draft-football) — F1 X-0 (2026-08-01)
- 🎮 [**PixelGP**](https://github.com/TeapoyY/app-pixelgp-web) — Turn-based racing + cards (2026-06-25)

## 🎮 How to Play

1. **Open `index.html`** in any modern browser (no build step, no dependencies)
2. **Draft 6 drivers** from across the 6 eras (1970s → 2020s)
   - Mix eras to unlock **Era Synergy bonus** (+1.5 OVR per extra driver from same era)
3. **Start the season** — your highest-OVR driver is your primary for all 36 races
4. **Simulate race-by-race** — win/lose is determined by OVR + track-type + variance
5. **Share your record** — the 36-0 / 35-1 / 30-6 shareable template is the viral hook

## 🏎️ The 96 Legends

6 eras × 16 drivers = 96 NASCAR legends, OVR-scaled 75-99:

| Era | Featured Legends | OVR Range |
|-----|------------------|-----------|
| 1970s | Richard Petty, David Pearson, Cale Yarborough, Bobby Allison | 75-99 |
| 1980s | Dale Earnhardt, Darrell Waltrip, Bill Elliott, Tim Richmond | 79-99 |
| 1990s | Jeff Gordon, Dale Jarrett, Rusty Wallace, Mark Martin | 75-99 |
| 2000s | Jimmie Johnson, Tony Stewart, Kevin Harvick, Matt Kenseth | 81-99 |
| 2010s | Kyle Busch, Brad Keselowski, Joey Logano, Martin Truex Jr. | 82-95 |
| 2020s | Kyle Larson, Chase Elliott, Ryan Blaney, Tyler Reddick | 78-95 |

## 🎲 Difficulty Curve (Monte Carlo, 1000 sims each)

| OVR | Avg Wins | 36-0 Probability | Experience |
|-----|----------|------------------|------------|
| 70 | 2.3 / 36 | 0.0% | Struggling backmarker |
| 80 | 11.5 / 36 | 0.0% | Mid-pack underdog |
| 85 | 17.6 / 36 | 0.0% | Competitive playoff bubble |
| 90 | 23.7 / 36 | 0.0% | Strong championship contender |
| 95 | 29.6 / 36 | 0.0% | Championship4 / title contender |
| 99 | 33.3 / 36 | 6.0% | All-time GOAT tier |

**Perfect 36-0** is achievable only with OVR 98+ rosters (rare ~3-6% of elite runs).
This keeps the shareable "I almost did it" tension.

## 🔵 Why NASCAR 36-0 (vs NBA 82-0 / NFL 38-0 / F1 24-0)?

| Factor | Status |
|--------|--------|
| **Blue ocean (Google Play)** | ✅ 0 draft apps for "nascar 36-0 draft" / "go undefeated racing season" (verified 2026-08-17) |
| **NBA 82-0** | ❌ Vaulty / Reign Collective already占领 |
| **NFL 38-0** | ⚠️ Sancar Media + we shipped (2026-07-30) |
| **F1 24-0** | ⚠️ We shipped (2026-08-01) |
| **NASCAR fanbase (75M+ US, "stock car country")** | ✅ Stable cultural footprint |
| **Multi-track discipline** (speedway/short/road/street/superspeedway) | ✅ Adds strategic depth vs single-track F1 |
| **Pack-racing chaos** (superspeedway) | ✅ "Gamble moments" — high risk / high reward |
| **Public player names** | ✅ Historical records, no licensing |
| **1-day MVP feasibility** | ✅ Single HTML, 96-row dataset |

## 🛠️ Tech Stack

- **Vanilla JS** — no npm, no build step
- **Single HTML file** — 40 KB, all logic inline
- **Mulberry32** — seeded RNG for reproducible seasons
- **Track-type modifiers** — 5 track types (speedway/intermediate/short/road/street/superspeedway)
- **Era synergy** — bonus OVR for same-era picks
- **Modern NASCAR points system** — 40-1 scale with positional falloff

## 📊 What Comes Next

- **Day 2**: GitHub Pages deploy → live web URL
- **Day 3**: Capacitor wrap → iOS TestFlight + Android Internal Testing
- **Day 4**: ASO keywords: "nascar draft", "nascar 36-0", "go undefeated racing season", "fantasy nascar draft"
- **Day 5**: Add playoff bracket mode (top 16 → 4-round elimination)

## 📄 License

Driver names are historical records (public domain). Team names are trademarks of their respective owners — used here for editorial / non-commercial fan tribute only.

---

🏁 *Built by [Hermes Cron](https://github.com/TeapoyY) — 1-day MVP, 2026-08-17*