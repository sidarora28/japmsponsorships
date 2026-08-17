# LinkedIn DM playbook

**This is now the primary outbound channel, ahead of email.** Reasons it wins:

- **No bounces.** The address problem that capped Day 1 at 2 of 10 disappears entirely.
- **The sender is known.** ~75,000 followers means a marketer at a dev-tool company has
  plausibly seen Sid's posts. A cold email is from a stranger; this isn't.
- **The proof is the product.** They can click the profile and see the audience they'd be
  buying, in one second. No media kit needed.

---

## The hard limits — plan around these

| | |
|---|---|
| **Connection invites** | ~100–200/week. LinkedIn throttles hard past this and will restrict the account. |
| **Invite note** | **300 characters.** Not 300 words. This is the real constraint. |
| **1st-degree DMs** | Unlimited in practice. Free. |
| **InMail** | Only with Premium/Sales Nav, ~20–50/month. Use sparingly on big targets. |

**~100 invites/week ≈ 20 per working day.** That is the real quota now — and it's *better*
than the email plan, because a 15% DM reply rate beats a 5% email reply rate by enough to
need far fewer touches.

> ⚠️ **Never buy an automation tool that auto-sends LinkedIn invites.** LinkedIn detects them
> and restricts accounts. A restricted profile costs the 75K audience — the entire asset the
> business runs on. Scraping to build a list is fine; automating the sending is not worth the
> risk. Sid sends these by hand, or not at all.

---

## Route 1 — Already connected (1st degree) 🔥 best

No character limit, no invite spent. **Check this first for every prospect.**

> Hey {{name}} — saw {{Company}} sponsored {{newsletter}} this month.
>
> I write JustAnotherPM for AI PMs — ~75k here on LinkedIn, 20k on the newsletter. Mostly
> senior product people at US/UK companies, exactly who you're going after with {{product}}.
>
> I'm booking Q4 sponsored posts. $1,500 for a post, $750 for a newsletter slot.
>
> Worth a look?

---

## Route 2 — Connection request + note (**300 characters, hard cap**)

The note has one job: get the invite accepted. **Do not try to close in 300 characters.**

> Hi {{name}} — saw {{Company}} in {{newsletter}} this week. I write JustAnotherPM (~75k
> followers here, AI PMs). Booking Q4 sponsor slots and think there's a fit — mind if I send
> details?

*(That's 214 characters. Count them — LinkedIn silently truncates.)*

**Then, the moment they accept**, send Route 1's full message. The acceptance *is* the
qualification: someone who accepts has looked at the profile and seen 75K followers.

---

## Route 3 — No connection, big target (Atlassian-scale)

Don't burn an invite on a stranger at a 10,000-person company. Instead:

1. Engage first — comment something genuinely useful on their post, twice, over a week
2. *Then* connect, referencing it
3. Or find the smaller fish: at big companies the person who buys creator media is a
   demand-gen or campaigns manager, not the CMO

---

## Sequence — 3 touches, then stop

| | When | What |
|---|---|---|
| **D1** | Day 0 | Invite + note, or full DM if 1st degree |
| **D2** | +5 days | *"Hey {{name}} — bumping this in case it got buried. Q4 slots still open."* |
| **D3** | +7 days after D2 | *"Last one from me — closing out Q4 bookings this week. Happy to revisit for Q1 if the timing's better."* |
| **Dead** | | Log it. **Never message again.** |

Same rule as email, and it matters more here: LinkedIn spam reports damage the account that
holds the entire audience.

---

## Rules

- **Lead with the observation, not the ask.** "Saw you sponsored X" proves this isn't a blast.
- **Rate in the first real message.** $1,500 post / $750 newsletter. Naming a number without
  hedging is what closed Airtable in a day.
- **Never paste the media kit.** The profile *is* the media kit.
- **Verified numbers only:** ~75K LinkedIn, 20,170 subscribers, **25.4%** open. Never 35%.
- **One specific true line per person.** 900 identical DMs gets the account restricted.
- Propose dates, **never confirm one.**
- Any discount ask, custom bundle, or non-cash offer → **Sid decides.** Not the desk.

## Log every one

Every DM goes in `pipeline/prospects.md` with `channel: linkedin` and the degree (1st/2nd/3rd).
Same ledger as email — **never double-touch someone on both channels**, which reads as
desperate rather than persistent.
