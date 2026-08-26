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
