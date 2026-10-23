---
name: halloa-product-context
description: Load before any Halloa.app marketing, sales, copy, ads, SEO, email, or pricing task. Holds the product facts, plans, prices, segments, competitors, voice, and decisions that every other skill must use. Also use when the user says "Halloa", "second number", or asks what we sell.
---

# Halloa Product Context

You are working on marketing and sales for **Halloa.app**. Use these facts instead of guessing. If a fact here conflicts with the live site (halloa.app/pricing), trust the site and flag the difference.

## The Product

- A **second US phone number on the phone you already have**. Calls and texts from an app, no second SIM or device.
- Two sides in one app:
  - **Individuals and Family**: privacy, travel, side work. No AI.
  - **Business**: same number plus an AI executive assistant ("Nora") that answers and summarizes calls.
- Telephony: Twilio. US texting needs 10DLC registration (1 to 3 days after signup).
- Site: halloa.app, Next.js on Vercel, 7 locales (en, he, ar, ru, es, zh, ja). Pages: /, /individual, /business, /pricing.
- **Status: pre-launch, waitlist mode.** Every CTA is "Join the waitlist". Never write copy that implies people can buy today unless told launch happened.

## Plans and Prices (as of 2026-10-20)

| Plan | Price | Notes |
|---|---|---|
| Personal | $12/mo | 2 numbers, US calls and texts, no stated cap |
| Family | $36/mo | Up to 5 people |
| Travel passes | $5 / 3 days, $8 / 7 days, $12 / 30 days | No auto-renewal |
| Business | $12/mo | Includes AI assistant |
| Organization | $6/user/mo | Minimum 5 users |
| Enterprise | Custom | |

- Trial: **1 day free, no card**.
- Annual plan: not decided yet (Linear HAL2-325). Do not quote an annual price.

## Decisions Already Made

- Waitlist incentive = early access only (no bonus days beyond the standard trial).
- Referral reward = 1 free day for both sides.
- No beta-tester quotes exist yet. **Never invent testimonials, user counts, or ratings.**
- Email provider: Resend.
- Waitlist segment chips: privacy, side business, online selling, travel, something else. No "Dating" chip.
- Show a public waitlist counter only after 500 signups.

## Segments (B2C)

| Segment | Pain | Core message | Main rival |
|---|---|---|---|
| Privacy (selling online, sign-ups, classifieds) | Personal number leaks to strangers and spam | Keep your real number private | Burner, Hushed |
| Travelers and expats | Lose US number abroad, 2FA breaks | Keep a US number anywhere | Slynumber, Google Voice |
| Side hustlers and freelancers | Work calls ring the personal line | Separate work line, same phone | Sideline, Line2 |
| Families | Kids and parents need numbers | One plan, up to 5 people | None direct |

## Positioning

Halloa is the **trusted, long-term second number for real life**: not a throwaway, no ads, no credits, a family plan, travel passes, and a no-card trial.

Proof points against rivals (full list: project file competitors/competitors.md):
- vs Google Voice: no existing US number needed to sign up, not taken back after inactivity.
- vs TextNow: no ads.
- vs Burner, Hushed, MySudo: unlimited use, no credits, family plan.
- vs Slynumber: no-card trial, family plan, travel passes, AI on Business.
- vs Sideline, Line2, Allo: AI assistant at $12.

Never disparage a competitor by name in ads. Compare pages may name them with facts and a date.

## Voice

- Plain, warm, confident. Short sentences. Second person ("your number").
- Concrete over clever: say what it does ("A second US number on your phone in 2 minutes") before any wordplay.
- No hype words ("revolutionary", "best-in-class"), no fake urgency, no emoji in headlines.

## Where Work Is Tracked

- Linear workspace cfir-main, team **Halloa** (prefix HAL2), label **Sales**.
- Marketing plan: Halloa B2C marketing plan (Claude Doc, 2026-10-22).

## Related Skills

copywriting, email-sequence, landing-cro, paid-ads, seo-content, app-store-optimization, paywall-pricing, lifecycle-retention, customer-referrals.
