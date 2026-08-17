# JustAnotherPM Sponsorship Desk

An agent that sources, prices, chases, and collects sponsorships for JustAnotherPM.
**Target: $8–10K/month**, against a ~$625/month run-rate today.

## Use it

```
/sponsorship-desk triage        # daily — sweep inbound, draft same-day replies
/sponsorship-desk backlog       # start here — $4–6K already on the table
/sponsorship-desk outbound      # weekly — 20–25 pitch drafts
/sponsorship-desk collections   # money already earned, stuck behind admin
/sponsorship-desk weekly        # Monday pipeline review
/sponsorship-desk close         # monthly revenue close
```

Or just ask: *"any sponsor emails?"*, *"what's in the pipeline?"*, *"who should I pitch?"*

## What's here

```
CLAUDE.md                 Always-loaded context: rules, cadence, diagnosis
knowledge/
  audience.md             The only numbers allowed in a pitch (25.4% open, not 35%)
  rate-card.md            $1,500 / $1,000 / $750 — the floor, and why it holds
  channels.md             The 5 rails, their reps, and how each one leaks
  target-brands.md        Outbound list, tiered by warmth
  the-gap.md              What 13–16× actually requires
pipeline/
  pipeline.md             Live deal state — the single source of truth
  backlog.md              $4–6K sitting untouched
templates/email/          Inbound replies, outbound pitches, collections
.claude/
  skills/sponsorship-desk/  The desk itself
  agents/                   inbound-triage · outbound-prospector · collections
  settings.json             Gmail send is denied at the permission layer
```

## The three rules that matter

1. **Nothing is auto-sent.** Everything is a draft Sid reviews. Enforced in `settings.json`,
   not just asked for.
2. **Never discount.** Card rates only. Anything below → Sid.
3. **Never quote 35%.** The real open rate is 25.4%.

## The diagnosis

Sid has ~75K LinkedIn followers and a proven $1,500 clearing price — Airtable said yes
same-day with zero negotiation. He closes about one deal a month at $735.

The constraint isn't demand or pricing power. **Inbound expires unanswered and nothing goes
outbound.** ~$3–4K of live inbound died in Apr–May 2026 alone, and three of the five rails
have earned money stuck behind an unfilled form or an unsent invoice.

So: answer everything same-day, collect what's owed, re-pitch the 20+ brands that already
paid, then go cold. In that order.
