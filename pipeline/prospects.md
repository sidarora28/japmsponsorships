# Prospect ledger

**Every company ever touched. Never delete a row. Check here before contacting anyone — a
double-touch is how you look like a spammer.**

Sequence: **T1** (day 0) → **T2** (+4 working days) → **T3** (+7 working days after T2) →
**dead**. Three touches, then stop permanently. **The clock starts on send, not on draft.**

Email column: `verified` (confirmed against a contact database or received from the person) or
`inferred` (pattern-guessed — expect ~30% bounce).

---

## Active sequence

| ID | Company | Vein | Contact | Email/channel | Seq | Last touch | Next due | Notes |
|---|---|---|---|---|---|---|---|---|
| O1 | **Allstacks** | A | **Hersh Tapadia (CEO) ✅ verified** — Gage Hollen purged (Planview); Emily Luehrs unverified | `hersh.tapadia@allstacks.com` **verified** | drafted 19 Aug, unsent | — | — | **Sponsored TLDR Product on BOTH 7 Aug and 11 Aug** — 4+ placements in 5 days. Most aggressive spender found. |
| O2 | **Enterpret** | A | — (Michelle Luo purged — works at Checkbox) | `marketing@` inferred | ✅ **SENT 19 Aug 08:45** | 19 Aug | chase 25 Aug | TLDR sponsor 12 Aug, Marty Cagan webinar 27 Aug. Sid also pinged their marketing lead on WhatsApp 17 Aug — handling direct. |
| O3 | **Atlassian** (Jira Product Discovery) | A | — | not found | not sent | — | — | TLDR Product main sponsor 11 Aug, eBook w/ Kyle Poyar + Aakash Gupta. Biggest budget, slowest close. Needs a named contact. |
| O4 | **WorkOS** | A | — (Shannon Elliott purged — works at Orca Security) | none | not sent | — | — | TLDR sponsor 12 Aug (Pipes). Dev-tool adjacent. Needs a fresh, verified contact. |
| O5 | **Gitar** | A | — | **scraper unusable — common-word name** | not sent | — | — | TLDR quick-link 12 Aug. AI code review. |
| O6 | **Granola** | A | — | **scraper unusable — common-word name** | not sent | — | — | TLDR AI sponsor 11 Aug. **AI notetaker — PMs are literally the user base.** Worth recovering by hand. |
| O7 | **Scribe** | A | — | **scraper unusable — common-word name** | not sent | — | — | TLDR AI sponsor 14 Aug. Process capture → "where AI delivers value". Product/ops buyer. |
| O8 | **Orkes** | A | — ("Amit Bhojraj" purged — profile resolves to a recruiter at WorkOS) | none | not sent | — | — | TLDR AI sponsor 11 Aug. Conductor — AI workflow orchestration, dev-facing. |
| O9 | **Elastic** | A | — | not found | not sent | — | — | TLDR Product sponsor 31 Jul. Search/AI platform. Large budget, slower cycle. |
| O10 | **Tines** | A | — | **scraper unusable — common-word name** | not sent | — | — | TLDR AI sponsor 17 Aug. AI agent/automation platform. IT-governance lean, weaker PM fit. |
| O11 | **PointFive** | A | — | **scraper unusable — common-word name** | not sent | — | — | TLDR AI sponsor 17 Aug. LLM cost analysis / token-spend reduction. **AI PMs own this problem.** |
| O12 | **Paved (Yuvna)** | Repeat | Yuvna Muthy Nunes | `yuvna@paved.com` verified | ✅ **SENT 19 Aug 08:41** | 19 Aug | chase 26 Aug | Sid rewrote the ask: matching Q4 campaigns **and recurring deals**, rather than naming Udacity/HubSpot. Better ask — recurring beats one-off and lets Yuvna surface brands we don't know about. |

### ✅ Verified and drafted, awaiting send — see `verified-contacts.md`

Allstacks (Hersh Tapadia, CEO) · Mixpanel (Paul Lenser, PMM) · Retool (Kelsey McKeon, Content
Marketing) · Productboard (Jordan Nolff, VP Growth) · Linear (Cristina Cordova, COO) ·
Vercel (Nicolas Kaden, Partnerships EMEA)

Held in reserve: David Hsu (Retool CEO), Hubert Palan (Productboard CEO) — only if the primary
contact goes quiet. Never both at one company in the same week.

### ❌ Purged 19 Aug — wrong company, do not contact

~~Lovable (Hayley W., Sam Vinden, Cameron Laird)~~ · ~~PostHog (Cleo Lant)~~ ·
~~Enterpret (Michelle Luo)~~ · ~~WorkOS (Shannon Elliott)~~ · ~~Allstacks (Gage Hollen)~~ ·
~~Retool (Mirko Brinker)~~ · ~~Orkes (Amit Bhojraj)~~

The scraper attributed all of these to companies they do not work at. Full evidence in
`verified-contacts.md`.

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
| **A** | Brands sponsoring comparable AI/PM newsletters | **Best by far.** Every company worth having came from here. |
| **B** | Companies hiring creator / influencer / dev marketing | Untested at scale |
| **C** | AI/dev tools funded in last 6 months | Untested |
| **D** | Competitors of past sponsors | Good on company selection (Mixpanel, Retool, Vercel verified). The *people* still needed verifying — PostHog and Lovable contacts were both wrong. |
| **E** | Brands running LinkedIn creator campaigns | Merges with D in practice |

**Vein A is renewable and barely tapped.** TLDR alone publishes Product, AI, Tech, Design and
Web editions with 2–3 sponsors each, most weekdays, with public archives at
`tldr.tech/<edition>/<YYYY-MM-DD>`. That is ~30 new qualified companies a week from one
publisher, before touching Lenny's, The Neuron, Ben's Bites or Superhuman AI.

**Method note — company-first works, title-first does not.** A title search (`fabri-lab`,
200 results across growth/PMM/demand-gen titles) returned 147 "candidates" but without company
attribution, mostly consultants and job-seekers. Unusable. Starting from a *known sponsor* and
scraping its employees gives candidates who are at least pre-qualified by the fact the company
buys this media — but see the audit note below on why those candidates still are not facts.

### ⛔ Scraper limit — stop paying to rediscover this

The employee scraper matches on **name**, not on a verified company entity. For companies
whose names are ordinary words it returns confident garbage rather than an error.

Two runs were burned proving it. Both slug guesses failed for the same five companies:

| Company | Attempt 1 | Attempt 2 | Returned |
|---|---|---|---|
| Granola | `granola-so` | `granolaai` | People who eat granola; a "Granny-O-La" founder; a CEO of an unrelated firm |
| Scribe | `scribe-how` | `scribehow` | Medical scribes; FirstHx staff; a content marketer at *Marketing Digest* |
| PointFive | — | `pointfive` | Marketing manager of **PointFive Band** |
| Tines | — | `tines` | Nothing |
| Gitar | `gitar-inc` | `gitar-ai` | One unverifiable profile with no company named |

⚠️ **Superseded by the 19 Aug audit.** An earlier version of this note claimed the scraper
"succeeded" on Allstacks, Lovable, Productboard, Mixpanel, Retool, Vercel, WorkOS and
Enterpret. The audit proved otherwise: **Lovable, WorkOS and Enterpret were wrong-company
attributions**, and Allstacks and Retool were each partly wrong. Returning a plausible-looking
row is not success.

**The real rule: the scraper produces candidate names, never confirmed facts.** Every candidate
must be checked against the email finder before it can be drafted against. See
`verified-contacts.md`.

**Do not attempt the five common-word companies again by guessing slugs.** Either open LinkedIn
and copy the real company URL by hand, or drop them. Granola is the only one worth the manual
effort — PMs are its user base — and even that is worth less than sending one message from the
verified list.

---

## Running totals

| | |
|---|---:|
| Companies sourced | 18 |
| Buyers named (raw, unverified) | 24 |
| **Buyers verified** | **8** |
| **Buyers purged as wrong-company** | **9** |
| **Messages sent** | **2** ✅ (Enterpret, Paved — 19 Aug) |
| Replied | 0 |
| Booked | **$0** |

**Watch the reply rate.** Under 2% after 200 sends means the email is wrong, not the market —
rewrite the template before sending another 200.

---

## ⚠️ The constraint — read this

**Sourcing is ahead of sending, and always has been.**

Six verified contacts are drafted and waiting, plus 8 warm re-pitches in `repitch-queue.md`.
Adding another 10 prospects a day to a queue that isn't being worked does not move $0 toward
$32,000.

**Read the daily quota as 10 _sends_, not 10 rows added to a file.** The pace table in
`target-32k.md` wants $2,000 booked by 31 Aug.

### Correction — the follow-up dates were fiction

Earlier runs recorded T2 follow-ups "due 21 Aug" for Allstacks and Enterpret. That was wrong:
**a follow-up cannot be due on a first touch that never went out.** The sequence clock starts
when a message is actually sent, not when a draft is written.

### Send status — 19 Aug

**First sends landed.** Sid sent two emails on 19 Aug:

| Time | To | Note |
|---|---|---|
| 08:41 | **Yuvna @ Paved** | Rewritten by Sid: asks for matching Q4 campaigns **and recurring deals** rather than naming Udacity/HubSpot. Better ask. Chase 26 Aug. |
| 08:45 | **Enterpret** | Sent as drafted. Chase 25 Aug. |

**Days elapsed: 3. Messages sent: 2. Booked: $0** — both went out this morning, far too early
for a reply.

Still sitting in drafts, unsent: **Varun (1stCollab)** from 17 Aug, plus the six verified
contacts drafted 19 Aug (Allstacks, Mixpanel, Retool, Productboard, Linear, Vercel). The Hugo
draft stays unsent by decision.

Sid reported the Varun email as sent on 17 Aug; it is still in the drafts folder and does not
appear in Sent. It may have gone from `sidarora87@gmail.com`, which this desk cannot see.
**Still unconfirmed.**
