# America250 — Claude Code Project Guide

## Who I am
- **Founder & CEO:** Duckson Cadet
- **Email:** ducksoncadet3@gmail.com | info@celebratebanner.com
- **Phone:** +1 772-834-9060
- **Business:** CDN4 LLC (DBA CelebrateBanner)
- **Address:** 211 Old Okeechobee Road, Bay 2 #1058, West Palm Beach, FL 33401

---

## What this project is
**America250** is a product suite built on top of the CelebrateBanner platform, targeting the **U.S. 250th Anniversary** (July 4, 2026). It includes custom banner templates, a government/institutional sales pitch deck, a dedicated landing page, outreach emails, and a partnership application to the America250 Foundation.

The goal is to position CelebrateBanner as the official custom photo banner provider for America250 celebrations — targeting schools, municipalities, event organizers, and government agencies.

---

## Live URLs
- **Landing page:** https://america-250.celebratebanner.com
- **GitHub repo:** ducksoncadet3-glitch/america-250
- **Main platform:** https://celebratebanner.com
- **Builder app:** https://app.celebratebanner.com

---

## Architecture

```
america-250.celebratebanner.com  → Vercel (static landing page)
GitHub: ducksoncadet3-glitch/america-250
```

- Static HTML/CSS/JS — no backend required for the landing page
- Banner builder is the same React app at app.celebratebanner.com
- Deploy workflow: Edit in GitHub web editor → Vercel auto-deploys

---

## Project Assets (completed or in progress)

| Asset | Status |
|-------|--------|
| SVG banner templates (America250 theme) | ✅ Built |
| Landing page (america-250.celebratebanner.com) | ✅ Live |
| Government pitch deck | ✅ Built |
| Outreach emails | ✅ Built |
| Partnership application to America250 Foundation | 🔄 In progress |
| America250 THEMES patch for builder (index.html) | ⏳ Pending upload |

---

## America250 Banner Theme Specs

### Design Direction
- **Patriotic** — red, white, blue, gold accents
- **Official-feeling** — suitable for government, schools, civic events
- Stars, stripes, and American Eagle motifs (generic — no licensed assets)
- Typography: bold serif + clean sans-serif pairing

### Layout Options
- Hero photo centered with patriotic frame
- Collage layout for community/group celebrations
- Text fields: Event name, date, location, optional tagline

### Output (same as all themes)
- Sizes: **24×36 in** and **18×24 in**
- Resolution: **300 DPI**
- Color mode: **CMYK**
- Formats: **PDF** (print-ready) **+ JPG** (digital)
- Bleed: **0.125 in** | Safe margin: **0.25 in**

---

## Target Customers

| Segment | Use Case |
|---------|----------|
| Schools & universities | Graduation + patriotic combo banners |
| Municipalities & city governments | July 4th celebrations, parades |
| Event organizers | America250 official events |
| Nonprofits & civic groups | Community celebrations |
| America250 Foundation partners | Official licensed use |

---

## Pricing (same platform)
| Product | Price |
|---------|-------|
| Digital Download | $19 |
| Printed Banner (24×36) | $49 |
| Printed Banner (18×24) | $39 |
| Bulk / institutional orders | TBD — pending Printmoz confirmation |

---

## Partnership — America250 Foundation
- Application in progress
- Goal: become an **official licensed vendor** for America250 celebrations
- Contact point: America250 Foundation partnership portal
- Key selling points: instant digital delivery, print-ready CMYK, no design skills needed, ships nationwide

---

## Pending Items
- [ ] Upload America250 THEMES patch to builder index.html
- [ ] Complete and submit America250 Foundation partnership application
- [ ] Define bulk/institutional pricing once Printmoz confirms reseller rates
- [ ] Add America250 theme to shared/themeConfig.json on main platform
- [ ] Update landing page with final pricing once confirmed
- [ ] Create social media campaign assets for July 4, 2026 launch

---

## Key Dates
| Date | Milestone |
|------|-----------|
| May 18, 2026 | Haitian Flag Day — separate campaign live |
| June 12, 2026 | World Cup 2026 opens — Watch Party theme live |
| **July 4, 2026** | **America250 — U.S. 250th Anniversary — main launch date** |

---

## Deploy Workflow
```
1. Edit files locally or in Claude Code
2. Open GitHub web editor → ducksoncadet3-glitch/america-250
3. Select All → Paste updated file → Commit
4. Vercel auto-deploys to america-250.celebratebanner.com
```

---

## Key Rules for Claude Code
1. **No licensed logos, flags, or official seals** — use generic patriotic motifs only unless America250 Foundation partnership is confirmed
2. **Always deliver complete files** — Duckson pastes full files into GitHub web editor
3. **CMYK + 300 DPI** is non-negotiable for all print outputs
4. **Do not update pricing** until Printmoz reseller rates are confirmed
5. Landing page must be **fast, static, mobile-friendly** — no heavy frameworks
6. When adding the America250 theme to the builder, update `shared/themeConfig.json` first — it is the single source of truth for both frontend and backend

---

## Connection to Main Platform
This project is a **theme + campaign extension** of CelebrateBanner. For full platform context (backend, Stripe, Cloudinary, Railway, etc.) see the main project's `CLAUDE.md` at:
```
bannercraft/CLAUDE.md
```

---

## Quick Start
```bash
# Clone and open landing page
cd america-250

# Edit and preview locally
open index.html

# Deploy: commit to GitHub → Vercel auto-deploys
```

---

## Acceptance Criteria
- [ ] Landing page loads in < 2s on mobile
- [ ] America250 theme available in builder at app.celebratebanner.com
- [ ] Partnership application submitted to America250 Foundation
- [ ] Banner templates render correctly at 300 DPI CMYK
- [ ] Pricing matches confirmed Printmoz reseller rates before go-live
