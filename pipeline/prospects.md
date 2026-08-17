# Prospect ledger

**Every company ever touched. Never delete a row. Check here before contacting anyone — a
double-touch is how you look like a spammer.**

Sequence: **T1** (day 0) → **T2** (+4 working days) → **T3** (+7 working days after T2) →
**dead**. Three touches, then stop permanently.

Email column: `verified` (found on a public page) or `inferred` (pattern-guessed from the
company's visible format — expect ~30% bounce).

---

## Active sequence

| ID | Company | Vein | Contact | Email/channel | Seq | Last touch | Next due | Notes |
|---|---|---|---|---|---|---|---|---|
| O1 | **Allstacks** | A | Emily Luehrs (VP Mktg) ⭐, Hersh Tapadia (CEO), Gage Hollen (PMM) | `marketing@` inferred + LinkedIn | T1 drafted | 17 Aug | T2 21 Aug | **Sponsored TLDR Product on BOTH 7 Aug and 11 Aug** — 4+ placements in 5 days. Most aggressive spender found. |
| O2 | **Enterpret** | A | — | `marketing@` inferred | T1 drafted | 17 Aug | T2 21 Aug | TLDR sponsor 12 Aug, Marty Cagan webinar 27 Aug. **Sid knows their marketing lead and pinged on WhatsApp 17 Aug** — warm, handle direct. |
| O3 | **Atlassian** (Jira Product Discovery) | A | — | not found | not sent | — | — | TLDR Product main sponsor 11 Aug, eBook w/ Kyle Poyar + Aakash Gupta. Biggest budget, slowest close. Needs a named contact. |
| O4 | **WorkOS** | A | pending | LinkedIn | not sent | — | — | TLDR sponsor 12 Aug (Pipes). Dev-tool adjacent. |
| O5 | **Gitar** | A | pending | LinkedIn | not sent | — | — | TLDR quick-link 12 Aug. AI code review. |
| O6 | **Granola** | A | pending | LinkedIn | not sent | — | — | TLDR AI sponsor 11 Aug. **AI notetaker — PMs are literally the user base.** Strongest new fit today. |
| O7 | **Scribe** | A | pending | LinkedIn | not sent | — | — | TLDR AI sponsor 14 Aug. Process capture → "where AI delivers value". Product/ops buyer. |
| O8 | **Orkes** | A | pending | LinkedIn | not sent | — | — | TLDR AI sponsor 11 Aug. Conductor — AI workflow orchestration, dev-facing. |
| O9 | **Elastic** | A | — | not found | not sent | — | — | TLDR Product sponsor 31 Jul. Search/AI platform. Large budget, slower cycle. |

### Queued in `dm-queue.md` — sourced, not yet contacted

Lovable (Hayley W., Influencer Marketing ⭐⭐) · Vercel (Nicolas Kaden) · Mixpanel (Paul Lenser) ·
PostHog (Cleo Lant) · Retool (Kiersten Davis) · Productboard (Megan Seidel) ·
Linear (Cristina Cordova) · Allstacks (Emily Luehrs)

**20 named buyers are sitting un-contacted.** See the constraint note at the bottom.

---

## Replied — moved to `pipeline.md`

| ID | Company | Contact | Replied | Outcome |
|---|---|---|---|---|
| — | | | | |

---

## Dead — no reply after T3

| ID | Company | Contact | T1 | T3 | Note |
|---|---|---|---|---|---|
| — | | | | | |

---

## Disqualified — researched, never contacted, and why

Logged so the same company isn't researched twice.

| Company | Sourced from | Reason |
|---|---|---|
| Scandit | TLDR Product 14 Aug | Barcode/ID scanning. An AI PM would not expense this. |
| Plaid | TLDR Product 31 Jul | Fintech fraud/risk. Wrong buyer entirely. |
| SANS | TLDR AI 14 Aug | Cybersecurity training. Security audience, not product. |
| Teleport | TLDR AI 14 Aug | Security infrastructure. Dev-security, weak PM overlap. |
| Shade | TLDR AI 11 Aug | AI agent pentesting. Security niche. |
| Statsig | LinkedIn scrape | Returned only engineers + 1 AE. No marketing contact. Retry later. |
| Dovetail | LinkedIn scrape | Every hit was a *different* Dovetail (Regulatory, + Co, Furniture, an OT practice). Wrong company. |

---

## Veins — rotate daily, don't drain one

| Vein | What | Yield so far |
|---|---|---|
| **A** | Brands sponsoring comparable AI/PM newsletters | **Best by far.** Every prospect worth having came from here. |
| **B** | Companies hiring creator / influencer / dev marketing | Untested at scale |
| **C** | AI/dev tools funded in last 6 months | Untested |
| **D** | Competitors of past sponsors | Strong — produced Mixpanel, PostHog, Retool, Lovable |
| **E** | Brands running LinkedIn creator campaigns | Merges with D in practice |

**Vein A is renewable and barely tapped.** TLDR alone publishes Product, AI, Tech, Design and
Web editions with 2–3 sponsors each, most weekdays, with public archives at
`tldr.tech/<edition>/<YYYY-MM-DD>`. That is ~30 new qualified companies a week from one
publisher, before touching Lenny's, The Neuron, Ben's Bites or Superhuman AI.

**Method note — company-first works, title-first does not.** A title search (`fabri-lab`,
200 results across growth/PMM/demand-gen titles) returned 147 "candidates" but without
company attribution, mostly consultants and job-seekers. Unusable. Scraping a *known
sponsor's* employee list yields ~1–3 real buyers per company, and every one is pre-qualified
by the fact that the company already bought this kind of media.

---

## Running totals

| | |
|---|---:|
| Companies sourced | 16 |
| Buyers named | 20 |
| **Contacted** | **2** (drafted, unsent) |
| Replied | 0 |
| Booked | **$0** |

**Watch the reply rate.** Under 2% after 200 sends means the email is wrong, not the market —
rewrite the template before sending another 200.

---

## ⚠️ The constraint has moved — read this

**Sourcing is no longer the bottleneck. Sending is.**

There are **20 named, qualified buyers in `dm-queue.md` that nobody has contacted**, plus 13
warm re-pitches in `repitch-queue.md` that have not gone out. Adding another 10 prospects a
day to a queue that isn't being worked does not move $0 toward $32,000.

**Read the daily quota as 10 _sends_, not 10 rows added to a file.** The pace table in
`target-32k.md` wants $2,000 booked by 31 Aug, which requires first contact this week.
Sourcing can be paused for several days without hurting the target. Sending cannot.
