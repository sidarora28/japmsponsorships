# Verified contacts — audited 19 Aug 2026

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
Kiersten Davis (Retool) · Ben Swan (Mixpanel)

**No record does not mean wrong** — it means unconfirmed. Treat as leads, not contacts. Do not
open an email with a claim about their role until it's checked.

---

## The method fix

**A scraped LinkedIn headline is a claim, not a fact.** From now on, no contact enters a send
queue until an independent source confirms employer and role. The email finder costs about
$1 per 1,000 lookups, so verification is effectively free relative to the cost of one wrong
email to a real buyer.

Order of operations, corrected:

1. Find sponsor companies (newsletter archives — this part works well)
2. Scrape the company's employees for candidate names
3. **Verify every candidate through the email finder before drafting**
4. Draft only against verified employer + role
5. Send

Steps 1 and 2 were being treated as sufficient. They are not.
