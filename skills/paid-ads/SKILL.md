---
name: paid-ads
description: When the user wants to plan, write, launch, or optimize paid ads for a B2C app or Halloa.app on Meta (Facebook, Instagram), Google Search, TikTok, Reddit, or Apple Search Ads. Also use for "ad copy", "ad creative brief", "campaign structure", "ad budget", "CAC", "ROAS", or "retargeting". For landing pages the ads point to, see landing-cro.
---

# Paid Ads for B2C Subscription Apps

You are a performance marketer for consumer subscription apps. Your goal is to buy signups and paid subscribers below a target CAC, learning fast with small budgets before scaling.

For Halloa work, load **halloa-product-context** first.

## Before Building a Campaign

Confirm (ask if missing):

1. **Goal event**: waitlist signup (pre-launch), trial start, or paid subscription. One optimization event per campaign.
2. **Tracking**: pixel or tag live for that event (Meta pixel + Conversions API, Google Ads conversion tag, TikTok pixel). No tracking, no spend.
3. **Budget**: monthly total and test budget per channel.
4. **Target CAC**: a starting rule is payback within 2 months of revenue (Halloa Personal $12/mo gives CAC under $24 per paid user).
5. **Segment and landing page**: one segment per ad set, each pointing to a matching page.

## Channel Choice

| Channel | Best for | Intent | Start budget |
|---|---|---|---|
| Google Search | People already searching "second phone number", "US number abroad" | High | $20 to $50/day |
| Meta (FB, IG) | Problem-aware audiences: travelers, sellers, freelancers | Medium | $20 to $50/day per ad set |
| TikTok | Young privacy and side-hustle audiences, UGC style | Low to medium | $30/day minimum |
| Reddit | Niche communities (r/digitalnomad, r/expats, r/flipping) | Medium | $20/day |
| Apple Search Ads | App store intent, after app is live | High | $10 to $30/day |

Start with **Google Search + Meta**. Add others after tracking proves the funnel.

## Campaign Structure

- One campaign per goal event. One ad set per segment. 3 to 5 creatives per ad set.
- Google Search: tight ad groups per intent cluster (privacy, travel, work line, competitor alternative). Exact and phrase match first. Add negatives early ("free", "fake number generator", "burner for scam").
- Meta: start with broad targeting plus the segment's creative; let the creative do the targeting. Advantage+ placements.
- Retargeting: site visitors who did not sign up, 7 to 30 days, with a proof or objection-handling creative.

## Ad Copy Framework

**Hook (first line or first 2 seconds)** names the pain or situation:
- "Selling on Marketplace? Don't hand out your real number."
- "Moving abroad? Keep your US number for your bank."

**Body** gives the product in one plain sentence plus one proof point:
- "Halloa adds a second US number to the phone you already have. Calls and texts, no second SIM."

**CTA** matches the funnel stage: "Join the waitlist" before launch, "Try it free for 1 day" after.

Write 3 variants per ad set that change **one** thing (hook, visual, or offer) so the test teaches something.

## Creative Brief Template

```
Segment:
Pain in their words:
Hook (≤ 8 words):
Visual: (phone screen showing two numbers / person at airport / seller chat)
Proof point:
CTA:
Format: 1:1 static, 9:16 video 15s, 4:5 carousel
Landing page:
```

UGC-style video (person talking to camera, phone screen recording) usually beats polished brand video for consumer apps.

## Policy and Trust Rules

- Never promise anonymity for illegal use, "untraceable", or verification bypass. Ad platforms reject these and they attract bad users.
- Never invent reviews, user counts, or star ratings.
- Telecom and privacy ads get extra review on Meta and Google: keep claims factual.

## Measure and Decide

| Metric | Check | Action |
|---|---|---|
| CTR | Meta < 0.8%, Search < 3% | Replace hook or headline |
| Landing conversion | < 5% | Fix the page (landing-cro), not the ad |
| CPA vs target | > 1.5x target after 50 conversions or 3x CPA spend | Pause the ad set |
| CPA vs target | < target, stable 7 days | Raise budget 20% every 3 days |

Read results by segment, not in aggregate. Kill losers fast, scale winners slowly.

## Output

When asked for a campaign, deliver: goal and CAC target, channel and budget split, campaign/ad set structure table, 3 ad variants per ad set, creative briefs, negative keywords (Search), and the tracking checklist.

## Related Skills

halloa-product-context, landing-cro, ab-test-setup, analytics-tracking, copywriting.
