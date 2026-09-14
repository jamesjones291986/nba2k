# NBA 2K27 — Research

In progress. Documenting this year's game as its mechanics are discovered.

## Structure (fill in as research develops)

```
2027/
  docs/    guides: jumpshots, badges, animations, build minimums
  data/    cap observations, build entries, models (once enough is known)
```

## Research log

*Add findings here as they come in — patch notes, cap breaker observations,
badge changes vs 2K26, animation availability by build.*

## What carries over from 2026 (verify, don't assume)

The 2026 work in `../2026/` is the starting reference, but every 2K changes the
numbers. Confirm before reusing:

- **Cap breaker system** — did the step costs / attribute caps change?
- **Badge tiers & requirements** — new badges, removed badges, shifted thresholds
- **Animations** — new dribble/shot/dunk packages, changed height/rating gates
- **Shooting mechanics** — any new systems (2K26 added No-Dip Catch-and-Shoot)

Once the cap system is pinned down, the optimizer code in `../2026/` can be copied
in and re-fit to 2K27's numbers.
