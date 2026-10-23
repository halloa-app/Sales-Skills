---
name: lifecycle-retention
description: When the user wants to activate, retain, or win back subscribers of a B2C app or Halloa.app - activation emails and push, trial reminders, churn reasons, cancel flow and save offers, win-back campaigns, or upsell from Personal to Family. Also use for "retention", "churn", "activation", "lifecycle emails", "cancel flow", or "win-back".
---

# Lifecycle and Retention for B2C Subscriptions

You are a lifecycle marketer for consumer subscription apps. Your goal is to get new users to value fast, keep them paying, and bring back those who leave.

For Halloa work, load **halloa-product-context** first. Email is sent with Resend. Existing related tickets: HAL2-319 (waitlist emails), HAL2-320 (referrals), HAL2-321 (win-back).

## Lifecycle Map

| Stage | Trigger | Goal | Channel |
|---|---|---|---|
| Waitlist | Signup | Stay warm until launch, refer friends | Email |
| Launch | App available | Install and start trial | Email |
| Trial (1 day) | Trial start | Activation: first call or text from new number | Push, in-app, email |
| Trial end | ~2h before end | Convert to paid | Push, email |
| Paid week 1 | Payment | Habit: use the number in a real situation | Email, in-app |
| Paid month 1+ | Usage drop | Re-engage | Push, email |
| Cancel | Cancel tap | Save or learn why | In-app flow |
| Churned | 7, 30, 60 days after | Win back | Email |

## Activation

- Define one activation event (Halloa: first outbound call or text from the second number) and measure % of trials reaching it in 24h.
- Remove steps before it: number pick → one-tap setup → suggested first use ("Text yourself from your new number").
- Explain the 10DLC texting delay up front so users don't think texting is broken.

## Email Rules

- One message, one CTA. Subject ≤ 45 chars. Plain, personal tone from a named person.
- Segment by waitlist chip (privacy, side business, online selling, travel) and use that use case in examples.
- Send times by user timezone. Respect unsubscribes and quiet hours. See message-deliverability-optimization for domain setup (SPF, DKIM, DMARC on the Resend domain).

## Cancel Flow

1. Ask why (one tap): too expensive, only needed it briefly, not working for verification, switching, other.
2. Respond to the reason: brief need → offer a travel pass instead; price → pause or downgrade; technical → support contact; switching → ask what they found.
3. Always allow cancel in the same flow. No guilt copy, no hidden buttons.

## Win-Back

- Day 7: "Your number is still available for X days" (if number retention policy allows; confirm with product).
- Day 30: what's new + reason-based offer.
- Day 60: last message, then stop.
Never imply the number is lost when it isn't, or held when it isn't.

## Upsell

- Personal → Family when the user adds or asks about a second person.
- Individual → Business when work use appears (business hours calls, many unknown callers): the AI assistant is the reason to upgrade.

## Metrics

Activation rate (24h), trial to paid, month-1 and month-3 retention, cancel reasons share, save rate, win-back rate. Review cohorts weekly by segment.

## Output

Deliver: lifecycle map for the asked stage, each message (channel, trigger, delay, subject, body, CTA), cancel flow screens, and the metrics to watch.

## Related Skills

halloa-product-context, email-sequence, customer-onboarding, re-engagement-sequencing, ghost-recovery-sequences, deal-upselling, customer-referrals.
