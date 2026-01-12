# CC-WEB Site Polish Sprint Plan
**Date:** 2026-01-12
**Context:** Pre-investor due diligence polish
**Status:** READY TO EXECUTE

---

## Decisions Made
- [x] Homepage layout: **Visual grouping** ("For Law Firms" section separate from "Other Tools")
- [x] Founder info: **Keep anonymous** (company-level trust signals only)
- [x] LocalTranscribe pricing: **$79 one-time purchase** (remove conflicting "$39-79/user monthly" references)
- [x] LocalTranscribe accuracy: Standardize on **85-92%** (remove/clarify 95-98% claim)

---

## P0 Tasks (Before Investor Calls)

### Task 1: Homepage Visual Grouping
**File:** `index.html`
**Lines:** ~1630-1720 (product cards section)

Changes:
1. Add "For Law Firms" section header before first product
2. Reorder cards: RevenueRescue → CASS Calculator → QuoteCreator
3. Add "Flagship" badge to RevenueRescue card
4. Add "Other Professional Tools" section header
5. Move: LocalTranscribe → ComplianceLogger under that header

### Task 2: Trust Signals (Anonymous)
**Files:** `index.html`, `revenuerescue/index.html`

On homepage:
- Add "3 products in production" or similar metric
- Add visible support email in footer or hero area
- Add money-back guarantee badge if applicable

On RevenueRescue:
- Add "Integrates with Clio via OAuth" badge/text
- Add "Your data stays in Clio" privacy reassurance
- Link privacy policy prominently

### Task 3: /lawyers Page Reorder
**File:** `lawyers/index.html`
**Lines:** ~794-936 (product sections)

Changes:
1. Lead with RevenueRescue (currently leads with LocalTranscribe)
2. Reframe header as "Clio-integrated tools for law firms"
3. Move "LocalTranscribe Features for Lawyers" section lower

---

## P1 Tasks (This Week)

### Task 4: LocalTranscribe Pricing Alignment
**File:** `localtranscribe/index.html`

Standardize on "$79 one-time purchase" - remove contradictory monthly pricing references:
- Line 18: Meta description says "$39-79/user monthly" → change to "$79 one-time"
- Line ~1153: Schema.org says "paid tiers from $39-79/user" → update
- Line ~1390: FAQ says "$39-79/user monthly plan" → change to "$79 one-time"
- Line ~1735: FAQ repeats "$39-79/user monthly plan" → change to "$79 one-time"

Also check/fix in related files:
- `lawyers/index.html` line ~868: "Volume pricing from $39-79/user monthly"
- `support/index.html` line ~854: Monthly tier pricing language

### Task 5: LocalTranscribe Accuracy Fix
**File:** `localtranscribe/index.html`

Changes:
- Keep "85-92% accuracy" as primary claim
- Modify FAQ answer (line ~1366) that says "95-98% for clear audio"
- Suggested fix: "85-92% accuracy, with higher rates possible for clear studio-quality audio"

### Task 6: Demo Video Embeds
**Files:** `revenuerescue/index.html`, `quotecreator/index.html`

- RevenueRescue: embed https://youtu.be/71UviCSALlk
- QuoteCreator: embed https://youtu.be/HduhBgkKW50

---

## Out of Scope
- No Clio badges/logos (no permission)
- No "Clio Approved" language (premature)
- No major redesign
- No new pages
- No investor-specific landing page

---

## Execution Order
1. Homepage visual grouping (P0) - ~45 min
2. Trust signals (P0) - ~30 min
3. /lawyers reorder (P0) - ~30 min
4. LocalTranscribe pricing fix (P1) - ~20 min
5. LocalTranscribe accuracy fix (P1) - ~15 min
6. Demo video embeds (P1) - ~20 min

**Estimated time:** 2-3 hours total

---

## Files to Modify (Summary)
- `index.html` - homepage product grouping + trust signals
- `lawyers/index.html` - reorder products, fix pricing reference
- `localtranscribe/index.html` - pricing alignment, accuracy claims
- `revenuerescue/index.html` - trust signals, demo video
- `quotecreator/index.html` - demo video
- `support/index.html` - pricing language alignment

---

*Prepared by CC-WEB | 2026-01-12*
