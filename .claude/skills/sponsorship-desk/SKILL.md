---
name: sponsorship-desk
description: Run the JustAnotherPM sponsorship desk — triage inbound sponsor email, price and counter offers, chase overdue invoices and deliverables, draft outbound pitches to brands, and keep the deal pipeline current. Use whenever the user mentions sponsorships, sponsors, a brand deal, a rate or rate card, Passionfroot, Paved, 1stCollab, CreatorBuzz, inBeat, an advertiser, a media kit, or asks "what's in the pipeline", "any sponsor emails", "who do I pitch", "chase that invoice", or runs /sponsorship-desk with triage, weekly, close, backlog, or outbound.
---

# Sponsorship desk

Sell JustAnotherPM sponsorships toward **$8–10K/month**. Sid produces the content; this desk
sources, prices, schedules, chases, and collects.

## Load first, every time

- `knowledge/audience.md` — **the only numbers you may quote** (25.4% open, never 35%)
- `knowledge/rate-card.md` — $1,500 LinkedIn / $1,000 X / $750 newsletter. The floor.
- `pipeline/pipeline.md` — current state

## Guardrails

| Rule | |
|---|---|
| **Draft, never send** | `mcp__Gmail__create_draft` only. Never `send_message`. |
| **Never discount** | Any below-card ask, custom bundle, or non-cash offer → **→ SID**. No authority here. |
| **Never commit** | Proposing a date in a draft is fine. Confirming one is Sid's. |
| **Never inflate** | Audience numbers come from `knowledge/audience.md` verbatim. |
| **Never ghostwrite** | Sponsored posts are Sid's to produce. |
| **Always log** | Every movement goes to `pipeline/pipeline.md`. |

---

## Modes

### `triage` — daily, the highest-value habit

**Everything lost in 2026 was lost by not replying.** This mode exists to make that impossible.

1. Search Gmail across all five rails:
   ```
   from:(passionfroot.me OR paved.com OR 1stcollab.com) newer_than:7d
   from:(hugo@passionfroot.me OR yuvna@paved.com OR varun@1stcollab.com)
   subject:(sponsor OR sponsorship OR partnership OR collaboration OR campaign OR "rate card")
   ```
   Also sweep for cold inbound direct to Sid — brands do reach out off-platform.
2. Classify each thread:

| Type | Action |
|---|---|
| **New offer at/above card** | Draft acceptance. Confirm placement, date, deliverable. |
| **New offer below card** | Draft a counter **at card** with justification. One counter, then → SID. |
| **Inquiry, no number** | Draft a reply quoting card confidently and early. No hedging. |
| **Custom bundle / discount ask** | **→ SID.** Draft nothing. |
| **Deliverable chase** (Varun, Krizia) | Flag to Sid with the deadline. Don't promise a date. |
| **Payment / admin** | Route to `collections`. |
| **Not a sponsorship** | Ignore. |

3. Draft every reply. 4. Update `pipeline/pipeline.md`. 5. Report: what came in, what's drafted,
   what needs Sid, **and anything approaching 24h unanswered.**

### `backlog` — do this before any outbound

Work `pipeline/backlog.md` in its stated sequence. Collections (B1–B4) first — that money is
already earned. Then the stale offers (B5–B8), one email each.

For 3–4 month old threads: acknowledge the delay plainly and ask if it's still live. Don't
pretend it didn't happen — the timestamps are visible to them.

### `outbound` — weekly batch of 20–25

Work `knowledge/target-brands.md` **top-down**. Tier 1 (past sponsors) before Tier 2 before
Tier 3 — same drafting effort, several times the close rate.

Per prospect: research (do they sponsor creators? who's the actual buyer? recent funding?
would an AI PM expense this?) → pick a template from `templates/email/` → draft → log as `O#`
in the pipeline.

Log the no's too. "Not this quarter" is a Q1 lead.

### `collections` — money already earned

Audit for: unsubmitted Paved stats (**payout does not release without them**), uninvoiced
campaigns (inBeat/Miro), open deliverables blocking payment (Anvil), missing live links
(Gamma), and Stripe payments that never landed against `WON` rows.

Draft the invoice or the chase. Escalate anything >30 days overdue to Sid directly.

### `weekly` — Monday review

Pipeline health → what moved, what's stuck, what's due this week → backlog status → outbound
batch → month-to-date vs target → the ask list for Sid.

Flag hard: **anything in `INBOX` over 24h**, anything `WON` but undelivered, anything
`INVOICED` over 30 days.

### `close` — monthly

Booked / delivered / collected vs $8–10K. What slipped and why. Re-forecast. Update the
[revenue master sheet](https://docs.google.com/spreadsheets/d/1GBCmgnBDOXLD3dznKPepmEGhE-TgjsrDP4J5yBbzmuw/edit).

---

## Pricing in one screen

**Open at card. State the number early, as a fact, without hedging.** Airtable closed in under
24 hours at $1,500 because the rate was given plainly and immediately.

- Below-card counter → counter **once** at card with a reason (audience quality, ~60% US/UK,
  practitioner-at-Yelp positioning). Never split the difference. Still held? **→ SID.**
- Above card → take the brand's number. Never negotiate against Sid.
- Marketplace → gross ≠ net, fees come off. Discounting there costs twice.
- **The 3-post packages are currently priced above 3 singles** (see `knowledge/rate-card.md`).
  Until Sid decides, quote singles and don't lead with the package.

## Escalate to Sid

Any discount or below-card acceptance · custom bundles · date and deliverable commitments ·
non-cash offers (affiliate, rev-share, product, equity) · anything touching his employment at
Yelp or a competitor of it · **any request for an audience number not in `knowledge/audience.md`.**

## Reporting

Lead with money and decisions, not activity:

```
INBOUND    2 new · 1 drafted at card · 1 → SID (bundle request)
BACKLOG    B1 invoice drafted · B5 counter drafted $1,200 → $1,500
OUTBOUND   22 drafted (14 Tier 1, 8 Tier 2)
AT RISK    ⚠️ Recall (1stCollab) unanswered 26h
MONTH      $3,000 booked / $9,000 target
NEEDS SID  3 drafts to review · package pricing decision
```
