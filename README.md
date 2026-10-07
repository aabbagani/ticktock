# TickTock: a concept for Vetcove Home Delivery

**Independent case study by Anvitha Abbagani, not an official Vetcove product.** Built from public
information only. The clinic, pets, people and orders are fictional, and the clock is simulated.

**Live:** https://ticktock.abbagani.com

When a clinic sells medication through a branded home-delivery storefront and an approved order
stalls at the vendor, the pet owner often finds out first. TickTock gives every approved order an
expected timeline. Five plain rules flag orders that stop moving, and the clinic gets an owned
exception ranked by how soon the pet runs out.

**What the prototype does** (styled after the patterns on Vetcove's public product pages; no Vetcove logo or brand assets):
- milestone rules R1–R5 → exception queue;
- urgency ranking by days of supply × drug tier, with a toggle to compare against days late;
- assign / acknowledge / resolve with an audit trail;
- a simulated clock that raises new stalls and auto-closes delivered orders;
- editable tiers;
- a "How it works" explainer.

**What it doesn't do:** suggested actions, approval-time warnings, real notifications, persistence,
or any connection to a real pharmacy or practice-management system.

It is one self-contained HTML file with no build step and no network calls. Open `index.html` in any
browser.
