## Site Build — paulgibbonsadvisory.com

### Stack
Astro + Vercel. No CMS. Content from markdown files and HTML model cards in this repo.

### Source Prototype
`site-prototype/index.html` — single-file HTML prototype (1566 lines). All design decisions are final. Split into Astro components.
Full handoff doc: `site-prototype/HANDOFF-CLAUDE-CODE.md`

### Design Tokens
```
--chocolate: #2c1e14       --espresso: #1a120b
--chocolate-mid: #3d2b1e   --cream: #f5f0e8
--chocolate-light: #4a3628 --gold: #b8922a
--ink: #0f0e0d             --paper: #f5f0e8
--mid: #6b6560             --light: #e8e2d8
```

### Four Accent Colors (cycle through all colored UI)
```
Blue:   #5BA3D9  (Leadership)
Green:  #3DCC80  (Change)
Purple: #B07DD6  (Governance)
Orange: #E8944A  (Strategy)
```

### Typography
- Bebas Neue — labels, nav, all-caps UI
- DM Serif Display — headlines, card titles
- DM Sans (300/400/500) — body

### Key Rules
- Dark background site (chocolate/espresso). Light cards use var(--paper).
- Service cards and pillar cards both use cream/paper backgrounds with dark text.
- All colored elements cycle through the four accent colors via data attributes.
- Model cards follow the design system in `change-agility/pillars/` — cream paper, two-column grid, Bebas Neue headers, DM Serif Display titles, red accent (#c84b2f).
- SHIFT Method on Pillar 6 is © Robert Meza, *Aim for Behaviour*. Always attribute.
- Trademarks: People-First™, Adaptive Adoption™, Accelerated Workforce™, Change Agility™

### Known Issues (priority order)
1. Hero image sizing broken — needs proper responsive handling
2. BrightSight Speakers link TBD (href="#" placeholder)
3. Footer social links are placeholders
4. Responsive polish needed below 900px
5. Logo strip is text-only — replace with SVGs when available

### Nav Structure
Home / Meet Paul / Corpus / Whitepapers / Keynotes / Engage

### GitHub
https://github.com/paulggibbons/adaptive_adoption (note: double g in paulggibbons)
