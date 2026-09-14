# NBA 2K

Research, documentation, and build analysis for NBA 2K, organized by game year.
Each year is its own game with its own caps, badges, and animations, so each lives
in its own folder rather than being merged.

## Structure

```
2026/   NBA 2K26 — complete. Build optimizer code, cap data, and guides.
2027/   NBA 2K27 — in progress. Research as the game's mechanics are discovered.
```

## Years

- **[2026](2026/)** — Cap breaker reverse-engineering tool + data, plus guides for
  jumpshots, badges, animations, and build minimums. Treat as the finished 2026
  reference.
- **[2027](2027/)** — New research for this year's game. Starts as documentation;
  the 2026 code can be copied forward and adapted once 2K27's cap/badge system is
  understood (it changes every game, so nothing carries over unverified).

## Working on a new year

1. Create a `YYYY/` folder.
2. Start with research/docs — badges, animations, cap observations.
3. Port and adapt the prior year's optimizer only after the new mechanics are known.
