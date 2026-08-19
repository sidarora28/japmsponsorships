# Prospect ledger

**Every company ever touched. Never delete a row. Check here before contacting anyone — a
double-touch is how you look like a spammer.**

Sequence: **T1** (day 0) → **T2** (+4 working days) → **T3** (+7 working days after T2) →
**dead**. Three touches, then stop permanently. **The clock starts on send, not on draft.**

Email column: `verified` (found on a public page) or `inferred` (pattern-guessed from the
company's visible format — expect ~30% bounce).

---

## Active sequence

| ID | Company | Vein | Contact | Email/channel | Seq | Last touch | Next due | Notes |
|---|---|---|---|---|---|---|---|---|
| O1 | **Allstacks** | A | Emily Luehrs (VP Mktg) ⭐, Hersh Tapadia (CEO), Gage Hollen (PMM) | `marketing@` inferred + LinkedIn | **drafted, never sent** | — | — | **Sponsored TLDR Product on BOTH 7 Aug and 11 Aug** — 4+ placements in 5 days. Most aggressive spender found. |
| O2 | **Enterpret** | A | Michelle Luo (VP Mktg) | `marketing@` inferred | **drafted, never sent** | — | — | TLDR sponsor 12 Aug, Marty Cagan webinar 27 Aug. **Sid pinged their marketing lead on WhatsApp 17 Aug** — warm, Sid handling direct. |
| O3 | **Atlassian** (Jira Product Discovery) | A | — | not found | not sent | — | — | TLDR Product main sponsor 11 Aug, eBook w/ Kyle Poyar + Aakash Gupta. Biggest budget, slowest close. Needs a named contact. |
| O4 | **WorkOS** | A | Shannon C Elliott (Field Marketing) | LinkedIn | not sent | — | — | TLDR sponsor 12 Aug (Pipes). Dev-tool adjacent. |
| O5 | **Gitar** | A | — | slug retry in progress | not sent | — | — | TLDR quick-link 12 Aug. AI code review. |
| O6 | **Granola** | A | — | slug retry in progress | not sent | — | — | TLDR AI sponsor 11 Aug. **AI notetaker — PMs are literally the user base.** Worth recovering. |
| O7 | **Scribe** | A | — | slug retry in progress | not sent | — | — | TLDR AI sponsor 14 Aug. Process capture → "where AI delivers value". Product/ops buyer. |
| O8 | **Orkes** | A | Amit Bhojraj (probable mktg), Maria Shimkovska (content) | LinkedIn | not sent | — | — | TLDR AI sponsor 11 Aug. Conductor — AI workflow orchestration, dev-facing. |
| O9 | **Elastic** | A | — | not found | not sent | — | — | TLDR Product sponsor 31 Jul. Search/AI platform. Large budget, slower cycle. |
| O10 | **Tines** | A | — | slug retry in progress | not sent | — | — | TLDR AI sponsor 17 Aug. AI agent/automation platform. IT-governance lean, weaker PM fit. |
| O11 | **PointFive** | A | — | slug retry in progress | not sent | — | — | TLDR AI sponsor 17 Aug. LLM cost analysis / token-spend reduction. **AI PMs own this problem.** |
| O12 | **Udacity + HubSpot** (via Paved) | Repeat | Yuvna Muthy Nunes | `yuvna@paved.com` verified | **drafted 19 Aug, unsent** | — | — | Both bought twice. One email covers both. Q4 run of 2–3 sends. |

### Queued in `dm-queue.md` — sourced, not yet contacted

Lovable (Hayley W., Influencer Marketing ⭐⭐) · Vercel (Nicolas Kaden) · Mixpanel (Paul Lenser) ·
PostHog (Cleo Lant) · Retool (Kiersten Davis) · Productboard (Megan Seidel) ·
Linear (Cristina Cordova) · Allstacks (Emily Luehrs) · WorkOS (Shannon Elliott) · Orkes

**24 named buyers are sitting un-contacted.** See the constraint note at the bottom.

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
| Sonatype | TLDR AI 17 Aug | Application security. Security audience, not product. |
| Amazon | TLDR Product 4 Aug | Promoting Mik Kersten's *Output to Outcome*. On-audience, but no reachable buyer at Amazon scale for a $1,500 placement. |
| Statsig | LinkedIn scrape | Returned only engineers + 1 AE. No marketing contact. Retry later. |
| Dovetail | LinkedIn scrape | Every hit was a *different* Dovetail (Regulatory, + Co, Furniture, an OT practice). Wrong company. |
| **Gamma** | — | **Dropped 18 Aug, Sid's call.** Undelivered Dec 2025 campaign written off. Do not contact. |
| **Passionfroot rail** | — | **Closed 18 Aug, Sid's call.** Hugo not contacted; Promoted and Rezonant no longer recoverable. |

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

**Slug warning.** The employee scraper matches on name, so a guessed company slug returns
garbage rather than an error — `granola-so` produced people who eat granola, `scribe-how`
produced medical scribes. Always confirm the real LinkedIn company URL before scraping, and
sanity-check that returned headlines actually name the company.

---

## Running totals

| | |
|---|---:|
| Companies sourced | 18 |
| Buyers named | 24 |
| **Messages sent** | **0** |
| Replied | 0 |
| Booked | **$0** |

**Watch the reply rate.** Under 2% after 200 sends means the email is wrong, not the market —
rewrite the template before sending another 200.

---

## ⚠️ The constraint has moved — read this

**Sourcing is no longer the bottleneck. Sending is.**

There are **24 named, qualified buyers in `dm-queue.md` that nobody has contacted**, plus 8
warm re-pitches in `repitch-queue.md` that have not gone out. Adding another 10 prospects a
day to a queue that isn't being worked does not move $0 toward $32,000.

**Read the daily quota as 10 _sends_, not 10 rows added to a file.** The pace table in
`target-32k.md` wants $2,000 booked by 31 Aug, which requires first contact this week.
Sourcing can be paused for several days without hurting the target. Sending cannot.

### Correction — the follow-up dates were fiction

Earlier runs recorded T2 follow-ups "due 21 Aug" for Allstacks and Enterpret. That was wrong:
**a follow-up cannot be due on a first touch that never went out.** Those rows are reset to
`drafted, never sent` with no next-due date. The sequence clock starts when a message is
actually sent, not when a draft is written.

### Send status — checked 19 Aug 06:10 UTC

**Day 3, still zero sends.** The Gmail drafts folder holds Varun, Hugo, Allstacks, Enterpret
(17 Aug) and now Yuvna/Paved (19 Aug). Nothing sponsorship-related has appeared in Sent at any
point since the queue was built.

Sid reported the Varun email as sent on 17 Aug. It may have gone from `sidarora87@gmail.com`,
which this desk cannot see. Unconfirmed.

**Days elapsed: 3. Messages sent: 0. Booked: $0.**

This is now the only number that matters. Added `pipeline/TODAY.md` — a single-screen file
with one priority action (reply to Optimizely, ~4 minutes) rather than a queue to work
through, on the theory that the blocker is friction rather than intent.
