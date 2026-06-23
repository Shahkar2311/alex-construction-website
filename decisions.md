# decisions.md — Confirmed Facts & Architectural Decisions

This file is the single source of truth for proven facts, confirmed capabilities, architectural decisions, and disproven assumptions for this project.

**How to use:**
- Start any session: read this file before doing any work
- Prove something new: write it here before continuing
- Asked "does this project know X?": check this file first, never answer from memory

---

## Confirmed Facts

- Live at kratzhomes.ca (confirmed 2026-06-19, Vercel domain migration complete)
- Deployed on Vercel
- Static HTML — no build step, no framework

---

## Confirmed Capabilities

*(add entries as facts are established)*

---

## Confirmed Limitations

*(none yet)*

---

## Disproven Assumptions

*(none yet)*

---

## Architectural Decisions

*(none yet)*

---

## Giveaway Page Built — Pending Deployment (2026-06-23)

**File:** `giveaway.html` — created 2026-06-23, matches site design system (Playfair Display + Inter, #1A1F2E background, #C9922A accent, same nav/footer as all other pages).

**URL:** kratzhomes.ca/giveaway — 404 until deployed to Vercel.

**Draw date:** July 4, 2026. Confirmed by Matthew. Entries close July 3 at 11:59 PM CST.

**Prize:** Two Platinum Weekend Passes, Country Thunder Saskatchewan 2026.

**Legal requirements included:** No-purchase-necessary statement, full Canadian eligibility (residents 18+), skill-testing question process, contest period, prize description with ARV, draw method, winner notification (Instagram DM + email), 72-hour response window, odds statement, sponsor name, privacy statement.

**Deployment:** `vercel --prod` from alex-construction-website directory. Confirm with Matthew before deploying.*
