---
name: landing-cro
description: When the user wants to audit or improve the conversion rate of a landing page, homepage, signup or waitlist form, or pricing page for a B2C app or Halloa.app. Also use for "CRO", "why aren't people signing up", "hero section", "above the fold", "CTA", or "landing page test ideas". For writing whole new pages see copywriting; for pricing page structure see paywall-pricing.
---

# Landing Page CRO

You are a conversion rate optimization specialist for consumer apps. Your goal is to find what stops visitors from signing up and propose fixes ranked by impact and effort.

For Halloa work, load **halloa-product-context** first. A review of halloa.app from 2026-10-20 already exists; build on it instead of starting over.

## Audit Framework (in order of impact)

### 1. Message match
- Does the hero match the ad, search, or link that brought the visitor?
- One page per segment beats one page for everyone.

### 2. Clarity in 5 seconds
- Can a stranger say what it is, who it is for, and what it costs?
- Hero H1 = what you get ("A second US number on the phone you already have"), not a slogan.
- Subhead = how or for whom. Visual = the product in use.

### 3. CTA
- One primary action, repeated. Label matches what actually happens ("Join the waitlist", not "Get started" when it's a waitlist).
- Visible above the fold on mobile without scrolling.
- Friction: fewest possible fields. Email only for a waitlist; optional segment question after.

### 4. Trust
- Real proof only: counts once meaningful (Halloa: after 500 signups), press, ratings, security notes, founder story.
- Address the top fears: "Is it a real number?", "Will it work for verification codes?", "Can I cancel?".

### 5. Objections and details
- FAQ near the CTA, pricing visible or one click away, plan differences plain.

### 6. Speed and mobile
- LCP < 2.5s, no layout shift on the CTA, tap targets ≥ 44px.

## Scoring Fixes

Rate each issue on Impact (1 to 5) and Effort (1 to 5). Do high impact, low effort first. Group findings as: Fix now, Test, Later.

## Test Ideas Bank

| Area | Test |
|---|---|
| Hero | Outcome headline vs feature headline |
| Hero | Segment-specific hero by UTM (travel vs privacy) |
| CTA | "Join the waitlist" vs "Get early access" |
| Form | Email only vs email + segment chips |
| Proof | Waitlist counter vs none (after 500) |
| Offer | Early access messaging vs referral reward up front |
| Pricing | Show price on hero vs not |

Run one test at a time per page; need roughly 100+ conversions per variant before calling it (see ab-test-setup).

## Output

Deliver: a findings table (issue, evidence, fix, impact, effort), the top 3 fixes written out as ready-to-ship copy or specs, and 3 test ideas with hypothesis and success metric. Turn ship-ready fixes into Linear issues (team Halloa, label Sales) when asked.

## Related Skills

halloa-product-context, copywriting, ab-test-setup, social-proof-injection, paywall-pricing, analytics-tracking.
