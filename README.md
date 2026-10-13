# CTD — Credenz Tech Dayz

**Credenz Tech Dayz (CTD)** is PISB's second flagship event after Credenz, held every year alongside the IEEE membership drive.

🌐 CTD '26: [ctd26.vercel.app](https://ctd26.vercel.app/)

## Editions

| Year | Website | Sessions / events material |
|---|---|---|
| **2026** | 🔜 *Coming soon* | 🔜 *Coming soon* |

## 📤 Where do I push?

| What you have | Put it in |
|---|---|
| **CTD website code** | `<year>/website/`, e.g. [`2026/website/`](2026/website/) |
| Event or session material (schedules, slides, rulebooks, problem statements) | `<year>/`, e.g. `2026/sessions/`, `2026/<event-name>/` |
| Notes for next year's team (what worked, vendors, timelines) | `<year>/README.md` |

```
ctd/
└── 2026/
    ├── README.md     ← what happened this edition, how to run/deploy the site, who built it
    ├── website/      ← CTD website code goes here
    └── sessions/     ← slides, schedules, rulebooks
```

**Deploying from this repo:** on Vercel or Netlify, set the project's *Root Directory* to `2026/website`.

New to Git? Follow [**How to push to PISB GitHub**](https://github.com/PICT-IEEE-Student-Branch/.github/blob/main/CONTRIBUTING.md).

## ⚠️ Before you push

- Never commit `.env`, API keys, database URLs or passwords. Commit a `.env.example` instead (`.env` is already in [`.gitignore`](.gitignore)).
- Never commit registration sheets, attendee lists, emails or phone numbers.

---

Part of the [PICT IEEE Student Branch](https://github.com/PICT-IEEE-Student-Branch) · See also [Credenz website](https://github.com/PICT-IEEE-Student-Branch/credenz-website)
