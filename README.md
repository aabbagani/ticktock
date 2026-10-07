# TickTock: a concept for Vetcove Home Delivery

**Concept mockup by Anvitha Abbagani, not a Vetcove product or screen. Made-up clinic and data.**
Built from public information only.

**Live:** https://ticktock.abbagani.com

When a clinic sells medication through a branded home-delivery storefront and an approved order
gets stuck, the pet owner often finds out first. TickTock flips that: the clinic hears first.

**What the prototype does:**
- Five plain rules flag stuck orders: not confirmed, not shipped, stuck in transit, backordered,
  autoship missed.
- The list is sorted by who runs out first. Only critical medicines turn red or amber.
- **Fix** suggests the fastest next step for that problem: offer pickup, nudge the pharmacy, wait
  for a new date, reship, switch to an alternative (vet approves), or send now.
- Orders move from Stuck to Waiting (with a date) to Done, with a history of who did what.
- Staff assignment, with a take-over lock so two people don't contact the same owner.
- Search, a Critical/Standard switch per medicine, and a one-screen "How it works."

**What it doesn't do:** real notifications or messages, logins, saved data, or any connection to a
real pharmacy or practice-management system. The demo dates follow the current week.

It is one self-contained HTML file with no build step and no network calls.
