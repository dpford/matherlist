# Camp Mather 2026 Waitlist Lookup

Find your true position on the Camp Mather 2026 waitlist.

The official waitlist PDF gives you a number, but not every family is competing for the same weeks or cabin sizes. This tool shows your actual position per week and cabin size — how many families ahead of you are requesting the same thing.

**Live site: [matherlist.vercel.app](https://matherlist.vercel.app)**

## How it works

Enter your waitlist number (1–1069) and see, for each week you signed up for:

- Your position for each cabin size you requested
- How many total families are requesting that cabin size that week
- Color-coded ranking: green (top 25%), yellow (25–50%), red (50%+)

## Technical details

Single `index.html` file — no frameworks, no build step, no external dependencies. All 1069 rows of waitlist data are embedded inline as a JS object. Position is calculated client-side by counting how many lower-numbered families also requested the same cabin size for the same week.

Data parsed from the official Camp Mather 2026 Waiting List PDF.
