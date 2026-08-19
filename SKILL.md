---
name: great-event-planning
description: >
  Plan and run a great side event at a conference: intimate dinners, cocktail evenings, breakfasts,
  or demo nights alongside a larger event (e.g., CFO dinner during HumanX). Produces an
  operating model, venue comparison table, venue detail cards, Luma copy, outreach sequences,
  LinkedIn posts, guest-list tracker, and run sheet. Use when someone mentions: planning a
  side event, hosting a dinner at a conference, co-hosting with a partner company, conference
  dinner planning, "dinner during [conference]", event outreach, venue scouting, curating a
  guest list, FOMO-driven invite strategies, or private-room restaurant events.
license: MIT
metadata:
  author: arnons1
  version: 1.0.0
---

# Great event planner

You are helping someone plan an intimate (but great!) side event alongside a larger conference. These events
are typically dinners, cocktail evenings, or breakfasts for 15-30 people, held at a restaurant
or private venue near the conference. They serve as relationship-building, brand-awareness, and
pipeline-generation tools.

The skill works in two phases:

1. **Setup** (first use): gather company context and produce a reusable **operating model**
   document the user keeps in Notion, Google Docs, or wherever they store playbooks.
2. **Event execution** (every event): read the operating model, then produce the specific
   artifacts needed for this event.

---

## Phase 1: Setup

If no operating model exists yet, run setup. The goal is to produce a document the user saves
and that you reference every time they plan a new event.

### 1.1 Discovery questions

Ask these to understand the company's event muscle. Adapt to what's already in the conversation.
Don't dump them all at once.

**Company & ICP:**
- Company name, what you sell, who buys it.
- Job titles of buyers AND the people one level below them. The layer below C-level is the one
  that actually shows up — they don't get invited to things as often and are usually happy to
  join a free meal. C-level gets invited to everything and often doesn't come.
- Cities/regions you operate in.

**Event identity:**
- Do you have an existing event series with branding (e.g., "Revenue Rendezvous")? If so,
  what's the name and where can I see past events?
- If not, do you want to create a named series for continuity, or keep events standalone?
- Preferred format: sit-down dinner (15-20 pax), cocktail/drinks (30-60 pax), breakfast
  (15-25 pax), demo night (50-200 pax), or flexible?

**Operations:**
- Budget range per event (rough). Typical sit-down dinners run €1,500-3,500 depending on city.
- How many of your own people attend? (Rule of thumb: max 3 per hosting company — 1 senior
  + 1-2 sales/GTM. More than that and guests notice it's a sales event.)
- Do you co-host with partner companies? What makes a good partner for you?
- Registration platform: Luma, Eventbrite, Splash, etc.?
- Qualifying questions for the registration form (e.g., "What ERP do you use?"). These double
  as lead-gen data.

**Post-event:**
- Where do contacts go after the event? (CRM, Google Sheet, etc.)
- Who is responsible for follow-up?

### 1.2 Produce the operating model

Based on discovery, produce a markdown document titled **"Side Event Operating Model"**.
This is the user's playbook. They'll store it wherever they keep company docs and edit it over
time. It should be complete enough that anyone on the team can pick it up and run an event.

The operating model must include these sections:

---

#### OPERATING MODEL TEMPLATE

```markdown
# [Company] Side Event Operating Model

## Identity
- **Series name:** [e.g., "Revenue Rendezvous" / standalone events]
- **Naming convention:** [Series Name]: [Theme] — [Conference] Edition
- **Tagline / positioning:** [One sentence: what are these events for]
- **Format:** [Sit-down dinner / cocktails / breakfast / etc.]
- **Target size:** [X] guests + [Y] per hosting company

## Target audience
- **Primary titles:** [e.g., CFO, VP Finance, Financial Controller]
- **Secondary titles:** [e.g., Pricing Manager, Revenue Operations, CRO]
- **The "one level below" insight:** [Describe who actually shows up and why]
- **Existing customers to invite:** [1-2 per event as friendly faces — list criteria]

## Co-hosting
- **Default approach:** [Solo / co-host / flexible]
- **Good partner profile:** [Overlapping ICP, non-competing product, willing to split
  costs and invite lists]
- **Cost split:** [Typically 50/50]
- **Headcount per company:** [Max 3 — 1 senior + 1-2 GTM]
- **Coordination:** Shared Slack channel, shared Google Sheet for guest list

## Budget
- **Range:** [€X – €Y per event, depending on city]
- **City benchmarks:**
  | City | Dinner (20-25 pax) | Cocktails (40-60 pax) |
  |------|--------------------|-----------------------|
  | [City] | €X,XXX | €X,XXX |
- **Budget principle:** Nice enough to be an attraction, not extravagant.
  Private room over main dining area, every time.

## Venue criteria
- Private room or clearly separated area (not just a reserved table in the main hall)
- Close to the conference venue — max 2 transit stops or 10 min walk
- Capacity matches target headcount (too big feels empty)
- The venue itself should be worth visiting — a place people are glad they went
- AV optional: only needed if running a fireside or short talk

## Timeline — the 3-phase operating cadence

### Phase A: T-6 to T-3 weeks (Setup)

| Task | Owner | Details |
|------|-------|---------|
| Confirm co-host | Marketing lead | Agree: format, date, cost split, team allocation. Set up shared Slack channel. |
| Set up registration page | Marketing lead | Luma (or equiv). Add co-host as editor. Require approval. Add qualifying questions. Don't open registration yet. |
| Scout & book venue | Whoever is local | Produce venue comparison table (see Venue Artifacts below). Get options on dates. Book once confirmed. |
| Build target guest list | Sales + Marketing | Sources: conference attendee list, CRM pipeline, LinkedIn search, personal network. 1-2 existing customers per company. Use shared Google Sheet. |
| Get conference attendee list | Sales team | Ask organizers, sponsors, delegation leads. This is the best source — do it early, it takes time. |

### Phase B: T-3 to T-1 weeks (Outbound & promotion)

| Task | Owner | Details |
|------|-------|---------|
| Wave 1: warm outbound | Everyone | Personal WhatsApp + LinkedIn DMs to known contacts. Send registration link only after a brief exchange — never cold. |
| Wave 2: expand outbound | Sales | LinkedIn DMs to target accounts from conference list. Personalized: "I'll be at [event] — we're hosting a small dinner the evening of [date], interested?" |
| LinkedIn promotion | Founders / senior people | Post from personal accounts, NOT company accounts. Pattern: "[Event name] during [Conference]. Small dinner, curated group. DM me if you're interested." Never post the registration link publicly. Tag co-host. |
| Track RSVPs | Marketing lead | Target: [X] confirmed guests. If short at T-2 weeks, expand invitations. |
| Follow-up sequence | Sales | Re-ping people who haven't responded. Name-drop confirmed guests or co-host. |

### Phase C: T-1 week to T+1 week (Execute & follow up)

| Task | Owner | Details |
|------|-------|---------|
| Final confirmations | Marketing lead | Send logistics email: venue address, time, any dress code. Brief the team on who's coming. |
| Confirm headcount with venue | Marketing lead | T-2 days. Final number to the restaurant. |
| Day-of execution | Senior person present | Arrive 30 min early. Flow: 30-40 min drinks → brief intro (senior person sets tone, everyone introduces themselves) → open conversation over dinner → close at stated time. Max one 10-15 min fireside if you have a big-name guest. |
| Content capture | Marketing / anyone | One takeaway, quote, or observation from the evening — feeds the content pipeline. Photos if appropriate. |
| Follow-up (within 48 hours) | Sales + Marketing | LinkedIn connections. Personal "great meeting you" message referencing something specific. Book follow-up meetings — try to get a slot before people leave the dinner. |
| CRM entry | Sales | All contacts in CRM with one-line context note: where met, what they do, what resonated. |
| Event report | Marketing lead | Fill in Notion (or equivalent): numbers, not vibes. Confirmed vs. showed, quality of conversations, leads generated, venue rating, what to change. |
| Debrief with co-host | Marketing lead | What worked, what to change. Share guest list with notes. Add venue to running "event-ready restaurants" list. |

## Outreach principles
- **Never post the registration link publicly.** Route interest through DMs. This creates
  exclusivity and FOMO.
- **Invite from personal accounts**, not company accounts. A human inviting > a brand inviting.
- **Double-inviting is fine.** If both co-hosts invite the same person, that's multi-threaded
  outreach — higher show rate.
- **Don't invite too early.** If the event is 8+ weeks out, people who confirm will forget or
  cancel. Build the list early, hold invites until T-5 weeks.
- **C-level minus one shows up.** Don't obsess over getting the CFO. The VP Finance, the
  Controller, the Head of Revenue Ops — they're grateful to be invited and more likely to come.

## Registration page
- **Platform:** [Luma / Eventbrite / etc.]
- **Approval required:** Always. Never open registration.
- **Qualifying questions:** [List them]
- **Capacity:** Set to target guest count (not target + buffer)

## Naming & continuity
- If running a named series: same branding and registration account across events.
  "[Conference] Edition" as subtitle.
- Reference past events in promotion: creates FOMO for people who missed earlier ones.

## Venue database
Maintain a running list of vetted venues by city:

| City | Venue | Capacity | Private room? | Cost range | Contact | Last used | Notes |
|------|-------|----------|---------------|------------|---------|-----------|-------|
```

---

Deliver this as a markdown file. Tell the user to save it where they keep company playbooks
(Notion, Google Docs, etc.) and update it after each event.

---

## Phase 2: Event execution

For each new event, start by reading the operating model (ask the user to share it if not in
the conversation). Then figure out which artifacts are needed.

### 2.1 Determine what's needed

Ask the user what stage they're at and what they need. The full artifact set is:

1. **Venue comparison table** — when scouting venues
2. **Per-venue detail cards** — for each shortlisted venue
3. **Registration page copy** — when setting up Luma
4. **Guest list tracker** — when building the invite list
5. **Outreach message sequences** — when starting outbound
6. **LinkedIn promotion post** — when ready to promote publicly
7. **Event-day run sheet** — for the team attending
8. **Post-event report template** — after the event

Don't produce everything at once. Produce what's needed now and offer the rest when the
user reaches that stage.

### 2.2 Event inputs

Gather these (skip what's obvious from context):

1. **Anchor conference:** name, dates, city, venue.
2. **Event format:** default to operating model preference.
3. **Date and time:** Before Day 1 is safest (travelers arrive the night before, no plans).
   During the conference works when guests are tired of sessions and want a quiet dinner.
   After the conference is risky — people leave early.
4. **Co-host:** partner company + contact, or solo?
5. **Target guest count.**
6. **Theme:** Broad enough for all hosts' audiences, specific enough to not be generic.
   Frame as a challenge the audience faces, not a product category.
7. **Big fish:** high-profile speaker or customer for a 10-15 min fireside? Optional but
   changes RSVP rates if you can name-drop on the invite.

---

### Artifact 1: Venue comparison table

When the user is scouting venues, produce a table with this structure. Research venues if
web search is available, or structure venues the user provides.

The table must have these columns — no shortcuts:

| Restaurant | Location (neighborhood + address) | Available [date]? | Space offered | Estimated cost — [X] guests | Key terms & notes | Notes (personal) |
|-----------|-----------------------------------|-------------------|---------------|---------------------------|-------------------|-----------------|

**For "Estimated cost":** break down the math visibly. Show per-person rate x guest count,
plus room hire, plus drinks package. Don't just show a total — the user needs to compare
line items across venues.

Example:
> 3-course €2,623.50 incl. BTW (€2,303.52 excl.)
> = dinner €55pp + 3-course drinks arr. €28.50pp + water €4.50pp + room €423.50

**For "Key terms & notes":** flag minimum spend requirements, deposit terms, cancellation
policy, and capacity constraints. Highlight any gotcha where the quoted package doesn't
meet the venue's own minimum spend.

**For "Space offered":** specify: fully private room (enclosed), semi-private area (not
sound-isolated), whole venue hire, or reserved section. This distinction matters — an open
area in a busy restaurant kills conversation at a dinner.

Each venue row should give the user enough information to make a decision without opening
another tab.

### Artifact 2: Per-venue detail card

For each shortlisted venue, produce a detailed card. This is what gets shared with the
co-host or sent to the team. Structure:

```markdown
## [Venue Name]
[Website URL]
**Address:** [Full address, neighborhood]
**Capacity:** [Private room capacity]
**Contact:** [Email, phone]

### About
[2-3 sentences: what makes this place interesting. Vibe, cuisine style, any notable features.
Not marketing copy — practical description.]

### Dinner menu ([typical service hours])
- 3 courses — €XX p.p.
- 4 courses — €XX p.p.
- [Additional options if available]

### Drinks
[List drink packages with prices: unlimited house wine/beer/soft, wine pairing per course,
welcome drinks. Show per-person rates and duration.]

### Tariffs & minimums
- Minimum spend: €X,XXX [+ service fee if separate]
- Deposit: €XXX [timing and refund terms]
- [Any surcharges: late hours, holidays, etc.]

### Extras
[Welcome bubbles, canapés, AV equipment, custom florals, name cards — with prices]

### Cost estimate — [X] guests · dinner

> [State any assumptions: which price list period, whether availability is confirmed]

**3-course option**
- Food: [X] × €[Y] = €[Z]
- [Drinks option]: [X] × €[Y] = €[Z]
- [Room/service fees]
- **Total ≈ €[Z]**

**4-course option**
- [Same breakdown]
- **Total ≈ €[Z]**

### Notes
- [Privacy level: whole-venue, enclosed room, semi-private]
- [Location convenience relative to conference venue]
- [Any risks: minimum spend not met by base package, sound isolation concerns, etc.]
- [Previous experience if the user has used this venue before]
```

### Artifact 3: Registration page copy

Follow this structure for Luma or equivalent:

```
[Series Name]: [Theme] — [Conference] Edition

[One paragraph: the tension or challenge the audience faces. We're not pitching a product, but focusing on a problem
as something they're already thinking about. If co-hosting, the theme must be broad enough
to cover both companies' audiences.]

[One paragraph: what happens at the event. Be specific about format.
"An invitation-only dinner for [X] [titles] exploring [theme]."
Name the co-hosts. Name the companies.]

Agenda:
[Time] — Arrival & drinks
[Time] — [Dinner / Discussion / Fireside] begins
[Time] — Close

Hosted by [Company 1] and [Company 2].
[One line about each company — what they do, not a marketing paragraph.]

This is an invitation-only event. Registrations are reviewed before confirmation.
```

**Registration settings to recommend:**
- Require approval (never open registration)
- Add qualifying questions from the operating model
- Capacity: set to target guest count (not target + buffer)
- If co-hosting: add co-host as editor so they can see registrations and tweak copy

### Artifact 4: Guest list tracker

Provide as a Google Sheets / CSV structure:

| Name | Title | Company | Source | Invited By | Invite Channel | Date Invited | Status | Notes |
|------|-------|---------|--------|------------|----------------|-------------|--------|-------|

**Source values:** Conference list, CRM, LinkedIn search, Personal network, Referral
**Status values:** Not yet invited, Invited, Reminded, Confirmed, Declined, No-show

Include a summary header: total invited, confirmed, confirmation rate, seats remaining.

### Artifact 5: Outreach message sequences

Produce 3 message variants per channel. Keep them short, personal, from a human.

**LinkedIn DM — warm contacts** (people you've met or are connected to):

Message 1 (initial invite):
> Hey [Name] — I saw you're going to [Conference]. We're hosting a small dinner on [date]
> for [titles/audience] to talk about [theme]. Only about [X] people, [venue area].
> Would love to have you. Want me to send the details?

Message 2 (follow-up, 5 days later if no response):
> Hey [Name], circling back — we've got a few spots left for [event name] on [date].
> [Name-drop one confirmed guest or the co-host]. I'm holding one space for you - let me know.

Message 3 (last nudge, 3 days before, only if they expressed interest but didn't register):
> Quick one — dinner is [day]. I'm giving the final headcounts to the restaurant, just want to make sure if you're still joining.
> I've got a few people on the waitlist if not.

**LinkedIn DM — cold contacts** (people you haven't spoken to):

Message 1:
> Hi [Name] — I'm [Your Name] from [Company]. We're organizing a dinner during [Conference]
> for [titles] to discuss [theme, framed as their challenge]. Small group, curated, no pitches.
> Would you be interested?

Message 2 (follow-up, 5 days later):
> Hey [Name], checking if this is something you'd be up for. We're at [X] confirmed and
> a couple of seats left, I really think you'd love it.

**WhatsApp — existing relationships** (keep it casual):

> Hey! Are you going to [Conference]? We're doing a dinner on [date] — small group,
> [theme], should be fun. You in?

### Artifact 6: LinkedIn promotion post

One post for personal accounts. Principles:
- Open with what you're doing, not why it matters
- Name the conference, the co-host, the city
- Don't link to the registration page — route interest through DMs
- Tag co-host's personal accounts
- 3-4 short paragraphs

### Artifact 7: Event-day run sheet

A one-page reference for the team on-site:

```markdown
# [Event Name] — Run Sheet

**Date:** [Date]
**Venue:** [Name, address]
**Venue contact:** [Name, phone]

## Team
| Who | Role | Phone |
|-----|------|-------|
| [Name] | Host / MC (does the intro) | |
| [Name] | Logistics (venue liaison, early arrival) | |
| [Name] | Guest relations | |

## Timeline
| Time | What | Who |
|------|------|-----|
| [T-30 min] | Arrive, check room setup, confirm with venue | Logistics lead |
| [Start] | Guests arrive, drinks | Everyone mingles |
| [+30 min] | Sit down. Senior host does 2-min intro: who we are, why we're here, theme. Ask everyone to go around: name, company, one sentence on what they're working on. | Host / MC |
| [Optional: +45 min] | 10-15 min fireside with [Big Fish Name] | Host / MC |
| [Dinner service] | Open conversation. No structured agenda. | |
| [End time] | Thank everyone. Mention follow-up. | Host / MC |

## Guest list (confirmed)
| Name | Title | Company | Invited by | Notes for conversation |
|------|-------|---------|------------|----------------------|

## Logistics
- [ ] Table cards / name cards ready
- [ ] Menu printed or confirmed with venue
- [ ] Photographer / content capture plan
- [ ] Wi-Fi password (for sharing if needed)
- [ ] Payment: [pre-paid / card on the day / invoice]

## Content capture
Assign one person to note down: one good quote, one interesting observation, one photo
opportunity. This feeds the content pipeline and the post-event LinkedIn post.
```

### Artifact 8: Post-event report template

```markdown
# Event Report: [Event Name]

**Date:** [Date]
**Venue:** [Name]
**Co-host:** [Company, if applicable]

## Numbers
- Invited: [X]
- Confirmed: [X]
- Showed up: [X]
- Show rate: [X]%
- ICP match rate: [X]% (how many guests matched your target profile)
- Follow-up meetings booked at event: [X]

## Guest quality
[1-2 sentences: was this the right crowd? Any surprising attendees?]

## What worked
[Bullet points]

## What to change
[Bullet points]

## Venue rating
- Food: [1-5]
- Space / privacy: [1-5]
- Location / convenience: [1-5]
- Value for money: [1-5]
- Use again? [Yes / No / Maybe]
→ Add to venue database: [Yes / No]

## Follow-up status
| Guest | Company | Follow-up sent? | Meeting booked? | Notes |
|-------|---------|-----------------|-----------------|-------|

## Content captured
- Quote: [...]
- Observation: [...]
- Photos: [Y/N, location]
```

---

## Co-hosting mechanics

When the event has a co-host, these agreements need to be nailed down early. Surface them
during planning, not as an afterthought.

- **Cost split:** typically 50/50.
- **Headcount per company:** max 3 (1 senior + 1-2 sales/GTM). Enforce this in the operating
  model — if 8 of 25 seats are sales reps, guests notice.
- **Guest list coordination:** shared Google Sheet. Both sides add names. Double-inviting the
  same person is fine — multi-threaded outreach increases show rate.
- **Luma access:** add co-host as editor so they can tweak copy and see registrations.
- **Registration questions:** each co-host can add one qualifying question (e.g., "What ERP
  do you use?").
- **Venue:** whoever is local scouts venues. The other side provides criteria and budget.
- **Promotion:** both sides post from personal LinkedIn accounts and tag each other.
- **Post-event:** share the guest list with notes. Both sides follow up independently.
- **Theme:** must be broad enough to cover both companies' audiences. Frame as a challenge
  the audience faces ("How getting bigger gets difficult") rather than either company's
  product category. If both companies address adjacent parts of the same workflow (e.g.,
  billing then ERP, or pricing then collections), find the umbrella.

---

## Guardrails

These are baked into the artifacts above, but worth restating because they're the most
common ways these events go wrong:

**Venue:** The venue must be close to the conference (max 2 transit stops or 10 min walk).
People are tired after a day of sessions — they will skip anything that requires a journey.
Always prioritize a private room over a semi-private area. If the venue only offers a
"raised podium" or "reserved section" in the main restaurant, flag this clearly — it works
for drinks, not for a dinner with conversation.

**Timing:** Don't start outbound invitations more than 5-6 weeks before the event. People
who confirm 8 weeks out forget or cancel. Build the guest list early, hold invites.

**Exclusivity:** The registration link never goes public. Route interest through DMs.
Post about the event on LinkedIn from personal accounts, but always end with "DM me if
you're interested" — never a link. This creates FOMO and lets you curate.

**Programming:** Don't over-program. One intro (2 min) plus optionally one 10-15 min
fireside. That's it. The rest is open conversation. Guests spent all day listening to
panels — they want to talk, not listen.

**Team staffing:** Max 3 people per hosting company. More than that and it stops feeling
like a peer dinner and starts feeling like a sales event.

**Follow-up:** Everything within 48 hours. LinkedIn connections, personal messages
referencing something specific from the conversation, CRM entries with context notes.
The dinner is the beginning of the relationship, not the end.

**Attendee list:** Get the conference attendee list early. Ask organizers, sponsors,
delegation leads. This is the best source for relevant invitees and it always takes
longer to get than you think.
