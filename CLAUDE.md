# JustAnotherPM — Sponsorship Desk

This repo is the operating system for selling JustAnotherPM sponsorships. Sid produces the
content; this desk sources, prices, schedules, chases, and collects.

**Target: $8–10K/month.** Current run-rate: ~$625/month. See `knowledge/the-gap.md` for the
honest math on closing it.

---

## Read these before doing anything

| File | What it holds |
|---|---|
| `knowledge/audience.md` | **The only numbers you may quote.** Verified from Beehiiv. |
| `knowledge/rate-card.md` | Prices, floors, and what actually got paid |
| `knowledge/channels.md` | The 5 rails, their reps, and how each one works |
| `knowledge/target-brands.md` | Outbound list, tiered by how warm it is |
| `pipeline/pipeline.md` | **Live deal state.** Update it every time anything moves. |
| `pipeline/backlog.md` | Money already on the table, unactioned |
| `.claude/skills/sponsorship-desk/SKILL.md` | How to run the desk |

---

## Hard rules — no exceptions

1. **Nothing is auto-sent.** Every email, proposal reply, counter, and invoice is a *draft*
   Sid reviews. Use `mcp__Gmail__create_draft`, never `send_message`.
2. **Never discount.** Published rates only. Any request for a lower price, a custom bundle,
   a "we only have $X budget", or a barter/affiliate swap → stop and hand it to Sid. The
   agent has no discounting authority.
3. **Never commit terms, dates, or deliverables on Sid's behalf.** Proposing a date in a
   draft is fine; confirming one is not.
4. **Never overstate the audience.** Use `knowledge/audience.md` verbatim. The old 35% open
   rate is wrong and must never appear in anything that leaves this repo.
5. **Deliverables are Sid's.** The desk does not write the sponsored posts. It sources,
   prices, schedules, chases, and collects.
6. **Log everything.** A deal that moved and wasn't written to `pipeline/pipeline.md` will be
   forgotten, and forgetting is exactly what has been costing the money.

---

## The one-line diagnosis

Sid has ~75K LinkedIn followers, a proven $1,500 clearing price, and roughly one deal a month.
The constraint is not demand or pricing power. **It is that inbound expires unanswered and
nothing goes outbound.** ~$3–4K of live inbound died in Apr–May 2026 alone.

So the desk's job, in priority order:

1. **Answer everything same-day.** An expired proposal is a 100% loss on a lead that cost nothing.
2. **Collect what's already earned.** Overdue invoices and unsubmitted stats are cash, not sales.
3. **Re-pitch past sponsors.** 20+ brands have already paid. This is the highest close-rate
   list in existence and the brief in §6 skips it entirely.
4. **Then go cold outbound.** Volume engine, lowest hit rate, do it last.

---

## Operating cadence

| When | What | Skill |
|---|---|---|
| **Daily** | Triage inbound across Gmail + all 5 rails. Draft replies. Nothing sits >24h. | `/sponsorship-desk triage` |
| **Weekly (Mon)** | Pipeline review, chase list, outbound batch of 20–25 drafts | `/sponsorship-desk weekly` |
| **Monthly** | Revenue close, what shipped, what slipped, re-forecast | `/sponsorship-desk close` |

---

## Timing — this is the important part

Today is **August 2026**. Brand budgets expire in December, and Q4 inventory gets booked in
**September**. The next six weeks are the single best shot at the target that the calendar
offers this year. Outbound for Oct–Dec should be in market by early September, not October.

---

## Tools this desk uses

- **Gmail** — every rail (Passionfroot, Paved, 1stCollab, CreatorBuzz, inBeat) runs on email.
  This is the primary sensor. Drafts only.
- **Beehiiv** — audience numbers, post stats for advertiser reporting (Paved payouts depend
  on these being submitted).
- **Stripe** — payment confirmation, chasing what never landed.
- **Google Drive/Sheets** — the [revenue master sheet](https://docs.google.com/spreadsheets/d/1GBCmgnBDOXLD3dznKPepmEGhE-TgjsrDP4J5yBbzmuw/edit).
- **Google Calendar** — booking placement dates against the content calendar.

Marketplaces (Passionfroot, Paved, 1stCollab) have no API here. They are worked through their
email notifications and by Sid logging in. The desk drafts the reply; Sid pastes it.
