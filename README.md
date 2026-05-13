# Hello Nancy Offsite 2026 — Deck

Goals, team allocations, and setup instructions for the May 2026 Hello Nancy offsite.

## View

Open `index.html` in any browser. Or publish to GitHub Pages and share the URL.

## Navigate

- **→** / **Space** / click right edge — next slide
- **←** / click left edge — previous slide
- **↑ ↓** — also work
- Swipe on mobile
- URL hash (`#5`) deep-links to a specific slide

## Edit

It's a single-file HTML deck. Open `index.html` in any editor.

- **Add/remove slides:** copy any `<div class="slide ...">` block, edit content, drop it where you want in the deck order.
- **Reorder:** drag slide blocks up or down in the source.
- **Change KPIs / team names:** find the slide block (each is commented like `<!-- ============ 07 · HELLO NANCY P1 ============ -->`), edit the text inline.
- **Headshots:** team cards currently use initial-circle placeholders (`<div class="team-avatar">IV</div>`). Replace with real photos like:
  ```html
  <div class="team-avatar" style="background-image:url('headshots/ivan.jpg');background-size:cover"></div>
  ```
  Drop photos in a `headshots/` folder next to `index.html`.

## Deploy to GitHub Pages

1. Push this folder to a new GitHub repo.
2. Repo Settings → Pages → Source: `main` branch, root.
3. Share the `username.github.io/repo-name/` URL with the team.

## Slide inventory (33 slides)

| #  | Slide                          |
|----|--------------------------------|
| 01 | Cold open hook                 |
| 02 | Title                          |
| 03 | The Goal — 13 brands           |
| 04 | The Rule — Day 3 ROAS          |
| 05 | Missions grid (all 13)         |
| 06 | What is a VSL                  |
| 07 | HN P1 — Meta VSL Ads           |
| 08 | HN P2 — Heyflow Quiz           |
| 09 | HN P3 — Text VSL Upsell        |
| 10 | Biird — Glass scale            |
| 11 | $0 → $1k cluster (7 brands)    |
| 12 | Friend brands (Scandic, Ruggie)|
| 13 | All 10 websites                |
| 14 | Team — Instructors             |
| 15 | Team — Scalers                 |
| 16 | Team — External                |
| 17 | Team — C&B                     |
| 18 | Team — Ally                    |
| 19 | CS team intro (Rach's read)    |
| 20 | CS — Lynn & Salman             |
| 21 | CS — Elle & Moeez              |
| 22 | CS — Hamza & DOS               |
| 23 | CS — Stella & Daphne           |
| 24 | Pre-checklist (Tuesday EOD)    |
| 25 | What to bring                  |
| 26 | Airport → iClub                |
| 27 | Setup intro                    |
| 28 | Accept Meta request            |
| 29 | Set up Claude Max              |
| 30 | Connect Gemini                 |
| 31 | VPN access                     |
| 32 | GitHub per person              |
| 33 | Let's go                       |

## Built from

Style cloned from [rsquaredboi.github.io/dtc-deck/hk-offsite-2026-v2.html](https://rsquaredboi.github.io/dtc-deck/hk-offsite-2026-v2.html).
