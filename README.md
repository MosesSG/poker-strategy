# Live Cash Poker Strategy System

A complete **3-bet or fold framework** for 1/2 and 2/5 No-Limit Hold'em live cash games.

Interactive, position-dependent range charts with mental model explanations for every decision.

🌐 **[View live site](https://yourusername.github.io/poker-strategy)**

---

## What's inside

| File | Description |
|------|-------------|
| `index.html` | Landing page — links to all charts |
| `ranges/calling-ranges.html` | Calling ranges by position vs EP/MP/LP opens (100BB & 200BB) |
| `ranges/iso-raise-ranges.html` | Iso-raise ranges vs 1 and 2+ limpers from BTN/CO/HJ/SB |
| `ranges/polar-3bet-ranges.pdf` | Original polar 3-bet range charts |

## Coming soon

- OOP post-flop framework (BB 3-bet pots)
- IP post-flop heuristics
- Poker math reference
- Mental models reference guide

---

## Folder structure

```
poker-strategy/
├── index.html              ← Landing page
├── README.md               ← This file
└── ranges/
    ├── calling-ranges.html
    ├── iso-raise-ranges.html
    └── polar-3bet-ranges.pdf
```

---

## Viewing locally

Just open `index.html` in any browser — no server needed. All charts are self-contained HTML files.

## Deploying to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/poker-strategy`
