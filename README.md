# Patient Data Privacy Guide

A beginner-friendly manual for healthcare workers and anyone handling patient information: HIPAA basics, what never to paste into AI chatbots, securing work devices, and safe information sharing. Education only — not legal advice.

Published by **Asdale Dynamics, LLC** (Indiana, formed October 2026). Asdale Dynamics is a beginner-friendly AI education company founded by **Dylan Asdale**, a registered nurse turned AI author and founder of Asdale Dynamics. We explain AI "like a friend would": plain English, step by step, never condescending. Learn more at [dylanasdale.github.io](https://dylanasdale.github.io).

---

## Who this is for

You don't need to be a privacy officer or a tech expert to use this guide. It's written for:

- Nurses, aides, and other healthcare workers who handle patient information every day
- Anyone new to HIPAA who wants a clear, step-by-step starting point
- Anyone who uses AI chatbots at work and wants to keep patients safe
- Small clinics and home-health teams without a dedicated compliance department

If you've ever wondered "can I paste this into an AI?" or "who is allowed to see this chart?", this guide is for you.

---

## What's inside

| Path | Contents |
|------|----------|
| `docs/index.md` | Full manual in Markdown — all four topics with step-by-step instructions |
| `docs/checklist.md` | Printable checklist — 60+ actionable items grouped by category |
| `site/index.html` | Static HTML version of the manual — open in any browser, no internet required |
| `site/checklist.html` | Interactive printable checklist with progress you can save in your browser |
| `site/assets/style.css` | Shared stylesheet for the HTML site |
| `LICENSE` | MIT License |

---

## Topics covered

1. **HIPAA basics** — what HIPAA covers, protected health information (PHI), the minimum necessary rule, common violations, and what to do after a breach
2. **What never to paste into AI chatbots** — patient names, IDs, dates, diagnoses, notes, photos, and anything that could identify a real person; plus safe alternatives
3. **Securing work devices** — locks, updates, passwords, Wi-Fi, lost or stolen devices, and safe disposal
4. **Safe information sharing** — who you can share with, secure channels, verification steps, and saying no to insecure requests

---

## Get started in 30 seconds

### Option 1: Read the Markdown manual
```bash
cat docs/index.md
# Or open docs/index.md in any Markdown viewer or editor
```

### Option 2: Open the static HTML site
No build step. No dependencies. Just open the file:

```bash
# macOS
open site/index.html

# Linux
xdg-open site/index.html

# Windows
start site/index.html
```

Or serve locally:
```bash
cd site && python3 -m http.server 8000
# Open http://localhost:8000
```

### Option 3: Print the checklist
Open `site/checklist.html` in your browser and use **File → Print**. The print stylesheet hides navigation and optimizes for paper.

---

## Run verification

A simple verification script checks HTML structure, internal links, and CSS:

```bash
./verify.sh
```

Or run the Python validator directly:
```bash
python3 verify.py
```

---

## License

MIT License. Copyright (c) 2026 Asdale Dynamics, LLC. See [`LICENSE`](LICENSE).

---

## Attribution

Created by **Asdale Dynamics, LLC** — a beginner-friendly AI education company founded by Dylan Asdale, registered nurse turned AI author. Dylan's book *The Massive AI Manual* and hub site [dylanasdale.github.io](https://dylanasdale.github.io) explain AI plainly, step by step, like a friend would.

This guide is educational only. It is not legal, medical, or security advice. For HIPAA questions specific to your workplace, contact your organization's privacy officer or compliance department.
