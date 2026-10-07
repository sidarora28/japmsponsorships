# Verified contacts — audited 19 Aug 2026, extended 26 Aug

**These are the only contacts confirmed to work where we think they work.**

Verified with Apify `snipercoder/linkedin-email-finder`, which returns each person's current
employer and work email from a contact database. Where it disagreed with the LinkedIn employee
scraper, the email domain matched the database's employer — so the database is treated as
correct and the scraper as wrong.

---

## ✅ Verified — email drafted and waiting in Gmail

| Company | Contact | Role | Email | Angle |
|---|---|---|---|---|
| **Allstacks** | Hersh Tapadia | Co-Founder & CEO | `hersh.tapadia@allstacks.com` | Sponsored TLDR Product on **both 7 and 11 Aug**. Proven, current spender. |
| **Mixpanel** | Paul Lenser | Product Marketing | `paul.lenser@mixpanel.com` | Amplitude — their direct competitor — already paid Sid $1,200. |
| **Retool** | Kelsey McKeon | Content Marketing Manager | `kelseymckeon@retool.com` | Airtable — their competitor — paid $1,500 same-day in Feb. |
| **Productboard** | Jordan Nolff | VP, Growth | `jordan.nolff@productboard.com` | Their buyer *is* this audience. Closest product-fit on the list. |
| **Linear** | Cristina Cordova | COO | `cristina@linear.app` | Near-total audience overlap. Rarely sponsors — asked honestly. |
| **Vercel** | Nicolas Kaden | Partnerships Lead EMEA | `nico.kaden@vercel.com` | v0 competes with Replit, who sponsored. London-based, same time zone. |

## ✅ Verified — held back deliberately

| Company | Contact | Email | Why held |
|---|---|---|---|
| Retool | David Hsu (Founder/CEO) | `david@retool.com` | Kelsey owns content marketing and is the right buyer. Only escalate to David if she goes quiet. |
| Productboard | Hubert Palan (Founder/CEO) | `hubert@productboard.com` | Same — Jordan first. Never both in the same week. |

---

## 🔺 Atlassian — leads found 26 Aug, unverified, LinkedIn-only

Atlassian has sponsored TLDR **three times in two weeks** (Product 11 Aug, AI 20 Aug, Product
25 Aug), twice for Jira Product Discovery specifically. Biggest budget on the list.

The employee scrape returned three plausible people. **The email finder has no record for any
of them**, so there are no addresses and no confirmed roles — these are leads, not contacts.

| Name | Headline (unverified) | LinkedIn |
|---|---|---|
| **Claire Drumond** | "Marketing Jira, Trello & Teamwork…" | `linkedin.com/in/claireefisher` |
| **Tanguy Crusson** | "Founded Jira Product Discovery" | `linkedin.com/in/tanguy-crusson-99832a` |
| Christopher Metoyer | "Brand Marketing at Atlassian" | `linkedin.com/in/christophermetoyer` |

**How to approach these safely.** The Lovable failure came from asserting a person's role
(*"you run influencer marketing at Lovable"*) on a scraped headline. That risk disappears if
the opener makes a claim about **the company** instead:

> *"Saw Jira Product Discovery in TLDR Product twice this month…"*

That is verified from the newsletters themselves. It stays true regardless of whether a title
is stale, so these can be approached on LinkedIn without waiting for verification.

**Claire Drumond first** — marketing is where a media budget sits. Tanguy is the JPD founder:
high influence, likely not the budget holder, worth a second touch if Claire goes quiet. Never
both in the same week.

## Figr AI — same situation

TLDR Product sponsor 25 Aug. Scrape found **Simón Solbas, "CEO @ Figr"** — no database record,
no email, and the profile slug is unconfirmed (two guesses both failed). At a company this
small the CEO is the right buyer. **Find the real profile by hand before approaching.**

---

## ❌ Purged — wrong company, do NOT contact

The LinkedIn employee scraper attributed these people to companies they do not work at. Every
one would have produced an embarrassing email opening with a false premise.

| Name | Scraper claimed | **Actually works at** |
|---|---|---|
| **Hayley Wade** | Influencer Marketing @ **Lovable** ⭐⭐ | Manager, Talent Ops @ **Twill** |
| **Sam Vinden** | Head of Growth Marketing @ **Lovable** | Head of Growth Marketing @ **Cleo** |
| **Cameron Laird** | Performance Marketing @ **Lovable** | Marketing Analytics @ **Cleo** |
| **Cleo Lant** | PMM @ **PostHog** | Director, Creative Solutions @ **Joyride** |
| **Michelle Luo** | VP Marketing @ **Enterpret** | Head of Marketing @ **Checkbox** |
| **Shannon Elliott** | Field Marketing @ **WorkOS** | Field Marketing Manager @ **Orca Security** |
| **Gage Hollen** | Product Marketing @ **Allstacks** | Manager, Product Marketing @ **Planview** |
| **Mirko Brinker** | GTM Leader @ **Retool** | Senior Manager Asia Sales @ **Branch** |
| **"Amit Bhojraj"** | Marketing @ **Orkes** | Profile resolves to **Anna Meyer, Recruiting Manager @ WorkOS** |

> **Lovable was the single worst error.** It was written up as "⭐⭐ best prospect on the entire
> list" on the strength of a job title — *Influencer Marketing* — that the person does not hold.
> All three Lovable contacts were wrong. The whole company entry was fiction.

---

## ⚠️ Unverified — no database record

Emily Luehrs (Allstacks) · Megan Seidel (Productboard) · Collin O'Brien (Productboard) ·
Karri Saarinen (Linear) · Nan Yu (Linear) · James Hawkins (PostHog) · Joe Martin (PostHog) ·
Kiersten Davis (Retool) · Ben Swan (Mixpanel) · the three Atlassian leads · Simón Solbas (Figr)

**No record does not mean wrong** — it means unconfirmed, and the database clearly has gaps
(it holds nobody at Atlassian, a company of 10,000+). Treat these as leads. Approach them on
channels that do not require an email address, and never open with a claim about their role.

---

## The method, corrected twice

**A scraped LinkedIn headline is a claim, not a fact.** No contact enters an *email* send queue
until an independent source confirms employer and role. The email finder costs about $1 per
1,000 lookups, so verification is effectively free next to the cost of one wrong email.

**But absence of a record is not a reason to stop** — it is a reason to change the opener. A
pitch that references something verified about *the company* ("you sponsored X on this date")
carries no false-premise risk regardless of the person's exact title, and can go out over
LinkedIn where no address is needed.

Order of operations:

1. Find sponsor companies (newsletter archives — this part works well)
2. Scrape the company's employees for candidate names
3. **Verify through the email finder**
4. **Verified** → draft an email against the confirmed role
5. **Unverified** → LinkedIn only, and open on the company fact, never the person's role
6. Send


---

## Added 8 September 2026 — Atlassian

| Company | Contact | Email | Source |
|---|---|---|---|
| **Atlassian** | **Christopher Metoyer, Sr Manager, Brand Creative Strategy** | `cmetoyer2@atlassian.com` | **Email finder — employer returned as a database field, not a scraped headline** |

**Why this matters more than one more contact.** Atlassian had been the strongest cold prospect
on the desk for three weeks — six TLDR placements in 18 days plus a dated event — but with no
email record it was queued as a LinkedIn DM. **No LinkedIn DM has ever been sent.** Email is
the channel that actually gets used here, so this moves Atlassian from a lane that has produced
nothing to one that has.

The finder returned **no record** for Claire Drumond (`claireefisher`) or Moksh Garg. Those stay
LinkedIn-only.

⚠️ **Christopher is brand creative, not media buying.** Claire Drumond owns Jira marketing and
would be the better buyer — but an imperfect contact on a working channel beats a perfect one
on a channel that never fires. The draft asks to be routed if he isn't the owner.

**One person per company.** Atlassian is now on the email rail; do not also DM Claire.


---

## Added 11 September 2026 — Pendo

| Company | Contact | Email | Source |
|---|---|---|---|
| **Pendo** | **Jennifer Peterson, Senior Director of Marketing, Global Brand and Content** | `jennifer.peterson@pendo.io` | **Email finder — employer returned as a database field, two matching records** |
| Pendo (backup) | Brett Baker, Director, Marketing Engineering | `brett.baker@pendo.io` | Verified, but wrong function — do not use unless Jennifer bounces |

**This is the best-qualified prospect the desk has produced.** Four things line up at once,
which has not happened before:

1. **Audience fit is total.** Pendo sells product analytics *to* product managers. Sid's list
   is product managers.
2. **They are spending on exactly this.** Learning Lab — free, self-paced courses on AI agents
   and product judgment, co-produced with **Mind the Product** — ran in TLDR Product on 8 Sep.
3. **The function is right.** Global Brand *and Content* is the person who buys content
   distribution, not an adjacent title hoping to route it.
4. **The email is verified**, not inferred, with two consistent records.

Compare with Atlassian, where the only verified contact is brand creative rather than media
buying. Here the contact and the budget are the same person.

Hook used: Learning Lab. It is specific, true, current, and the placement being pitched is the
one that sells courses.

No record for Laura Baverman.


---

## 🚨 2 October — the drafts were in the wrong mailbox the whole time

A draft audit found `sid@justanotherpm.com` — **the mailbox Sid actually works from** — held only
**one** sponsorship draft (Outskill). Everything else sat in `sid.arora.87@gmail.com`.

`create_draft` has no "from" field; it lands drafts in whichever account the connector resolves
to, and that changed partway through. So nine finished drafts were written to an inbox Sid does
not open for business email.

**That is a large part of why six weeks of drafts produced zero sends.** The queue existed; he
could not see it.

**All verified contacts were re-drafted into the business mailbox on 2 Oct:**

| Company | Contact | Email | Hook used |
|---|---|---|---|
| **Atlassian** | Christopher Metoyer, Sr Mgr Brand Creative Strategy | `cmetoyer2@atlassian.com` | State of Product 2027 report, TLDR 2 Oct |
| **Pendo** | Jennifer Peterson, Sr Dir Mktg, Global Brand & Content | `jennifer.peterson@pendo.io` | Learning Lab w/ Mind the Product |
| **Allstacks** | Hersh Tapadia, CEO | `hersh.tapadia@allstacks.com` | 3 TLDR placements in August |
| **Mixpanel** | Paul Lenser, Product Marketing | `paul.lenser@mixpanel.com` | Amplitude already sponsored |
| **Retool** | Kelsey McKeon, Content Marketing | `kelseymckeon@retool.com` | Airtable paid $1,500 same-day |
| **Productboard** | Jordan Nolff, VP Growth & Product | `jordan.nolff@productboard.com` | Audience is their buyer |
| **Linear** | Cristina Cordova, COO | `cristina@linear.app` | Honest long shot, total overlap |
| **1stCollab** | Varun | `varun@1stcollab.com` | Q4 inventory + Recall + Optimizely repost |
| **Product-Led Alliance** | Fiona Standen, Marketing Manager | `fiona@pmmalliance.com` | Reviving the March conversation |

### ✅ Net-new verified 2 Oct

| Company | Contact | Email | Source |
|---|---|---|---|
| **Algolia** | **Robin Smith, Interim Head of Growth** | `robin.smith@algolia.com` | Email finder — employer returned as a database field. Scraped headline ("Leading Product-Led Growth @ Algolia") corroborates |

Hook: their hallucination-mitigation white paper, TLDR AI 1 Sep.

**No record** for Stella Resta (content marketing manager @ Fullstory, headline self-named) or
Laura Hamilton (CMO, no company named). Fullstory remains unsourced for email despite being a
strong fit — they sponsored TLDR Product 2 Oct on digital friction.

### Standing rule added

**Check which mailbox a draft landed in.** The `viewUrl` in the create_draft result names the
account (`authuser=…`). Any sponsorship draft not in `sid@justanotherpm.com` is invisible.


### ❌ Rejected 2 Oct — three headline/domain mismatches

Checked nine profiles today. **One verified (Algolia). Three were near-misses that a scraped or
web-searched headline would have sent to the wrong company:**

| Candidate | Headline claimed | Email finder returned | Verdict |
|---|---|---|---|
| Hollie Wegman | Marketing leadership @ **Attio** | Company "Attio" but email **`hollie@envoy.com`** | ❌ Contradictory record. Domain beats label |
| Jeremy Lee | Product Marketing @ **Attio** | **Ramp** — `jlee@ramp.com` | ❌ Wrong company |
| Jack Eaton | B2B Marketing @ **Modash** | **Peak Reach** (his own company) — `jack@peakreachmedia.com` | ❌ Wrong company |

**New rule, and the sharpest version of the Lovable lesson: when the email domain contradicts
the claimed employer, the domain wins.** Hollie Wegman's record literally says Attio while
handing back an `envoy.com` address. Either the record is stale or the fields are merged from
two sources. Not usable either way.

> ### 🔧 Refined 5 Oct — the rule was too blunt
>
> A fuller scrape showed Jeremy Lee's own headline reads **"Product Marketing at Attio |
> Ex-Ramp."** So the email finder returning `jlee@ramp.com` was not a wrong-company error — it
> was a **stale record**. He moved to Attio and the database hasn't caught up.
>
> **Corrected rule:** the domain still wins for *deciding whether to send* — `jlee@ramp.com`
> reaches him at the wrong employer and is unusable. But "wrong company" and "stale record" are
> different diagnoses, and a headline saying **"Ex-<company>"** is strong evidence of the latter.
>
> Practical consequence: **a stale record means no usable address, not a disqualified person.**
> Jeremy Lee stays a live Attio candidate awaiting an address from another source. Hollie Wegman
> (record says Attio, email says Envoy, no "Ex-" signal) stays genuinely ambiguous.

### 📉 Honest yield rate

Nine profiles checked, five returned no record at all, three were wrong-company, **one was
usable.** That is roughly **1 verified net-new contact per 9 profiles**, and each profile costs
a lookup.

Also no record for: Stella Resta (content marketing manager @ Fullstory — headline self-named),
Adam Gunn (VP of Brand @ Fullstory), Will R. (Field & Partner Marketing @ WorkOS — LinkedIn slug
is literally `will-workos`), Laura Hamilton (CMO, no company named).

**Fullstory and WorkOS both have named, plausible marketing leads and no obtainable email.**
They stay unsourced rather than drafted to a guess.

**Implication for volume:** this toolchain produces 1–2 verified net-new contacts per working
session, not ten. Getting to ten a day needs a real contact database with seats (Apollo, Clay,
Hunter), not an email-finder with a one-in-nine hit rate.


---

## 🔑 5 October — the best contact source yet: people who have already emailed Sid

Mined Gmail for brand- and agency-side senders rather than scraping LinkedIn. **Every address
below is verified by the fact that it reached his inbox**, and most come with an existing
relationship. Zero lookup cost, no bounce risk, no wrong-company risk.

| Contact | Org | Email | Status |
|---|---|---|---|
| **inBeat Agency** | Miro Canvas 26 | `miro@inbeatagency.com` | 🔴 **Owed money.** Invoiced 17 Jul, unpaid |
| **Nicole J** | **Miro** (brand side) | `nicole.j@miro.com` | Sid pitched Q4 on 25 Aug, no reply |
| **Erwin Nurhuda** | Hockey Stick agency, repping **SureThing** | `erwin.nurhuda@hockeystick.io` | Emailed twice in July, **never answered** |
| **Valentina Diaz** | **CreatorBuzz** (ran Anvil) | `valentina@creatorbuzz.com` | Active agency relationship |
| **OMANE Media** | ran **Viktor** campaign | `hi@omane.media` | Active; Viktor is a repeat TLDR sponsor |
| Lucas Page | ShanghAI newsletter | `lucas.page119@gmail.com` | Cross-promo (barter — Sid's call, not cash) |
| Marcel | Rad Letters | `marcel@radletters.com` | Directory listing, low value |

**Why this beats cold sourcing.** Nine LinkedIn lookups on 2 Oct produced one usable address.
One Gmail search on 5 Oct produced **five**, all with history. Agencies are the better target
too: CreatorBuzz, Hockey Stick, OMANE and inBeat each carry a roster, so one relationship
yields repeat campaigns rather than one placement.

**Standing change: mine the inbox before scraping LinkedIn.**


### 📊 Cold sourcing vs inbox mining — the comparison is now conclusive

Second cold batch on 5 Oct: scraped Modash, Attio, WorkOS, Elastic and Temporal (53 profiles),
filtered to five marketing titles, ran the finder on three of the best.

| Candidate | Title | Finder returned |
|---|---|---|
| Mike Lee | **VP, Brand & Demand Marketing at Elastic** | no record |
| Steve Ruiz | Growth @ WorkOS | no record |
| Maxwell Berry | Top of Funnel @ Attio | **PlusPlus** — `max@plusplus.co`, stale |

**Zero usable.** Running cold total: **1 usable address from 12 lookups.**

Against that, one Gmail search on 5 Oct produced **five verified contacts with existing
relationships** and one overdue invoice worth chasing.

| Method | Lookups / searches | Usable verified contacts |
|---|---:|---:|
| LinkedIn scrape → email finder | 12 | **1** |
| Mine Sid's own inbox | 1 | **5** |

**Conclusion: cold LinkedIn sourcing is not worth the time at this hit rate.** The inbox,
agency rosters (CreatorBuzz, Hockey Stick, OMANE, inBeat), the Beehiiv advertiser list and past
sponsors are all better sources, and they arrive warm.

Elastic, WorkOS, Attio and Modash all have named, plausible buyers and **no obtainable address**.
They stay unsourced. Mike Lee at Elastic is the single best title found all week and there is no
way to reach him with these tools.


---

## 6 October — second inbox sweep. Nine more verified contacts and two more unpaid bills.

| Contact | Org | Email | Why it matters |
|---|---|---|---|
| **Kenta Tanaka** | **Fotor** | `kenta.tanaka@fotor.com` | ⚠️ **Unanswered paid-collab offer, 18 Sep.** Came to Sid |
| **Katie Green**, Principal Advocate | **Kameleoon** | `kgreen@kameleoon.com` | 🔥 **Best net-new prospect.** Sid sat on their ETLA awards jury, so warm — and Kameleoon is a direct Optimizely competitor, a category that has already paid |
| **Elophia Mengestu** | CreatorBuzz | `elophia@creatorbuzz.com` | 🔴 **Owed money.** Promised net-30 on 10 Aug; window closed early Sep |
| **Vin Matano** | CreatorBuzz | `vin@creatorbuzz.com` | Sends the contracts — the decision-maker |
| **Ori Mannheim** | OMANE Media | `hi@omane.media` | **Does 3–5 launches a week.** Highest-frequency buyer found |
| Santiago Gomez | inBeat | `santiago@inbeat.agency` | Alternate route for the unpaid invoice |
| Juana Coutoune · Valerie Mariano | inBeat | `juana.coutoune@inbeat.agency` · `valerie.mariano@inbeat.agency` | Same |
| Aida | Miro | `aida@miro.com` | Miro-side, cc'd on Canvas 26 |
| Chelsea · Delaney | Maven | `chelsea@maven.com` · `delaney@maven.com` | Partnerships team — course business, not sponsorship |

**Nicole Judson's title confirmed:** Influencer Marketing Manager @ Miro. That is exactly the
person who buys creator placements, which makes the unanswered 25 Aug pitch more valuable than
it looked.

### 🔴 The OMANE history I didn't have yesterday

Yesterday's OMANE draft was a breezy Q4 pitch. The thread shows something worse:

- **17 Jun** — Ori offers a Viktor amplification post at $400. Sid counters $700.
- **18 Jun** — Ori: *"I can do $500 this time and increase the budget moving forward. I have three to five launches a week, and I'll be happy to include you in more."*
- **21 Jul** — Ori: *"Both drafts have been with you since the 15th and I haven't heard back, and the roster for this round is now full, so we're not moving ahead this time."*

**A recurring buyer at 3–5 launches a week was lost to silence.** Draft rewritten to open by
owning that rather than pretending it didn't happen — an agency that volunteered to raise its
budget deserves the apology before the pitch.

### Money owed — now two, not one

| | Owed by | Status |
|---|---|---|
| Miro / inBeat | `miro@inbeatagency.com` | Invoiced 17 Jul, "with accounting" 30 Jul, **unpaid 2+ months** |
| **Anvil / CreatorBuzz** | `elophia@creatorbuzz.com` | Net-30 promised 10 Aug, **expired early Sep, nothing received** |

Both chases drafted. Content delivered and impression data supplied in both cases, so neither
has an outstanding obligation on Sid's side.

### Running source comparison

| Method | Attempts | Usable verified contacts |
|---|---:|---:|
| LinkedIn scrape → email finder | 12 lookups | 1 |
| **Inbox sweeps (5–6 Oct)** | **2 searches** | **14** |

Not close.

---

## 7 Oct 2026 — the contact-discovery wall comes down

Three separate entries in this file said some version of *"named, plausible buyer, no
obtainable address."* That was the binding constraint on the whole desk. It is fixed.

**What changed:** every previous attempt searched **LinkedIn profile → email**. Today's tool
searches **domain → decision makers**. You hand it `fullstory.com` and a seniority band and
it returns named people with work emails, titles, departments, and a position history whose
`current: true` entry says whether they still work there.

`snipercoder/decision-maker-email-finder` on Apify. Input: `{domain, decision_maker_category
(ceo_founder_owner | director_head_president | manager_entry_intern), max_leads_to_find}`.
Roughly **$1 per 1,000 emails**.

### Yield, against the two methods already tried

| Method | Attempts | Usable verified contacts |
|---|---:|---:|
| LinkedIn profile → email finder *(retired 5 Oct)* | 12 lookups | 1 |
| Inbox sweeps | 2 searches | 14 |
| **Domain → decision makers** | **12 domains** | **38 marketing contacts** |

### It also solves the stale-record problem by itself

The 2 and 5 Oct entries in this file are a long argument about whether a contradictory record
means "wrong company" or "stale". This tool answers it in the data. The position history
carries a `current` flag, so a record resolves itself:

| Record | Label said | `current` said | Verdict |
|---|---|---|---|
| Lisa Hrabosky | VP Bank & Network Partnerships, Marqeta | **Identifee** | Stale — do not use |
| Amanda Volz | VP Global Customers, Thorn | **Volz Consulting** | Stale — do not use |
| Jim Walker | VP Product Marketing, Temporal | **Jackrabbit Industries** | Stale — do not use |
| Whitney Blankenship | Sr Content Marketing, Modash | **Whitticisms** | Stale — do not use |
| Kristin Mills | VP Growth & Demand Gen, Fullstory | **FullStory** | ✅ Current — pitched |

**New rule, replacing the domain-beats-label rule:** filter on the `current: true` employer in
position history. Where it disagrees with the headline, the position history wins, and the
contact is dropped rather than argued about.

### Contacts pitched 7 Oct — all confirmed current

| Company | Person | Email | Title |
|---|---|---|---|
| Fullstory | Kristin Mills | `mills@fullstory.com` | VP, Growth & Demand Generation |
| Temporal | Mike Pace | `mike@temporal.io` | Head of Demand Gen & Lifecycle Marketing |
| WorkOS | Amit B | `amit@workos.com` | Head of Marketing |
| Elastic | Rhodes Klement | `rhodes.klement@elastic.co` | VP Corporate Marketing |
| Attio | Tristan Morgan | `tristan.morgan@attio.com` | Growth Marketing |
| Level Access | David Schweer | `david.schweer@levelaccess.com` | VP, Product Marketing |
| Thorn / Safer.io | Justus Hyatt | `justus.hyatt@wearethorn.org` | Marketing Director |
| Marqeta | Mark Cousins | `mcousins@marqeta.com` | VP, Global Demand Gen \| EU Marketing |

### Held in reserve — verified, current, not yet contacted

One person per company is the rule, so these are backups if the primary goes silent past T3.

| Company | Person | Email | Title |
|---|---|---|---|
| Attio | Ilan C | `ilan@attio.com` | Head of Product Marketing & Comms |
| Fullstory | Bekkah Sappington | `bekkah@fullstory.com` | Director of Marketing Operations |
| Fullstory | Natasha Kading | `natashakading@fullstory.com` | Sr Manager, Integrated & ABM |
| Temporal | Kelly Bakalich | `kelly.bakalich@temporal.io` | Senior Demand Generation Manager |
| Elastic | Gagan Singh | `gagan.singh@elastic.co` | VP, Product Marketing |
| Level Access | Abby Moore | `abby.moore@levelaccess.com` | Director of Field Marketing |
| Modash | Ryan Prior | `ryan@modash.io` | Head of Marketing |
| Kameleoon | Helene Batard | `hbatard@kameleoon.com` | Growth Marketing Manager |
| Kameleoon | Olivia Scholes | `oscholes@kameleoon.com` | Senior Marketing Manager, North America |

**Kameleoon already has a live draft to Katie Green (6 Oct)** — these two are strictly
fallbacks, do not double-contact.

### Where the tool returns nothing

`redis.io` and `redis.com` both returned a single empty row. Redis is a real prospect — it ran
a `paid-newsletter` UTM in TLDR AI on 5 Oct, so the budget line exists — but this tool cannot
see it. Not every domain is covered, and an empty result means "not in the database", not
"nobody works there."

### Modash — sourced, deliberately not pitched

Ryan Prior is verified and current. I did not draft to him. Modash sells to **influencer
marketing managers**; this audience is product managers. Pitching it would mean writing a
line about audience fit that isn't true. Logged as a real contact for when there is a reason.
