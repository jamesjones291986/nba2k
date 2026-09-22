# NBA 2K27 Motion Styles — Requirement Reference

Motion style = how your player **moves/dribbles up the court** (idle-to-move
animation), separate from dribble moves and size-ups.

> Source: lockercodes.io motion styles page (verified Sep 3, 2026). 353 packages
> total; the page's pagination is client-side JS, so **rows 1–100 are verified here**
> and 101–353 could not be retrieved (not reproduced rather than invented).

---

## How motion styles gate — this is the key difference

- **Gated by BOTH Agility (AGI) and Speed (SPD)** — you must meet *both* — plus a
  height range. **Ball Handle does NOT gate motion styles** (that's dribble moves).
- The list is **unified** — offensive and defensive are not split into separate lists
  on this page.
- This matters for build planning: a motion style you want may require Speed/Agility
  your build didn't invest in. A slow big can be locked out of a snappy guard motion
  even with high Ball Handle.

## Tiers by Agility + Speed (from the verified subset)

**Fast/agile (AGI 68+, SPD 74+) — guards/wings:**
- Amen Thompson (70/77), Ausar Thompson (72/75), Anthony Edwards (68/75),
  Donovan Mitchell (68/76), Alex Caruso (71/66), Derrick White (70/70),
  Dennis Rodman (70/68), Devin Carter (67/74)

**Mid (AGI 55–66, SPD 55–70) — most builds:**
- Damian Lillard (65/66), Darius Garland (66/70), Dennis Schroder (66/67),
  Coby White (64/68), Collin Sexton (66/70), CJ McCollum (63/66),
  Dejounte Murray (64/66), DeMar DeRozan (60/63)

**Low (AGI ≤54, SPD ≤55) — bigs / low-mobility:**
- Al Horford (50/42, 6'5–7'4), Brook Lopez (45/25, 6'10+),
  Domantas Sabonis (37/38, 6'10+), Donovan Clingan (34/35, 6'10+),
  Clint Capela (38/46, 6'10+), Alperen Sengun (48/42, 6'10+)
- **Base** (0/25) — the universal fallback, 5'9–7'4

## Big-man motion styles (6'10+, verified subset)

Low AGI/SPD requirements — reachable by a paint big / point center:

| Package | AGI | SPD | Height |
|---------|----:|----:|--------|
| Donovan Clingan | 34 | 35 | 6'10+ |
| Domantas Sabonis | 37 | 38 | 6'10+ |
| Clint Capela / Alex Len | 38 | 46 / 34 | 6'10+ |
| Damian Jones / Cody Zeller | 41 | 50 / 56 | 6'10+ |
| Dereck Lively II | 43 | 40 | 6'10+ |
| Brook Lopez | 45 | 25 | 6'10+ |
| DeAndre Jordan | 47 | 52 | 6'10+ |
| Alperen Sengun | 48 | 42 | 6'10+ |
| Deandre Ayton | 49 | 60 | 6'10+ |
| Danilo Gallinari / Bol Bol | 51 | 48 / 54 | 6'10+ |
| Alexandre Sarr | 54 | 58 | 6'10+ |
| Chet Holmgren | 56 | 60 | 6'10+ |
| Anthony Davis | 59 | 63 | 6'10+ |

**For the point center:** since motion styles need Speed + Agility (not Ball Handle),
and your build's Speed/Agility are modest (~64–79 Speed, ~50–54 Agility on the verified
center builds), you can comfortably equip the low-AGI big styles above. Chet Holmgren
(56/60) is the snappiest big style your mobility likely reaches; **Base** always works.

---

## Key principles

1. **Motion styles gate on Speed + Agility, not Ball Handle** — a distinct budget.
   Don't assume a fast motion is available just because your handle is high.
2. **Height-banded like layups** — bigs (6'10+) have their own low-AGI/SPD styles;
   guard motion styles are height-locked out.
3. **Base (0 AGI / 25 SPD)** is the universal fallback if nothing else qualifies.

> **Confidence note:** requirements verified from lockercodes (Sep 3, 2026), **first
> 100 of 353 packages only** — the rest couldn't be paginated and are omitted rather
> than guessed. No "best" ranking is published free; this is requirements + tiering.
> 2K27 is early; reqs can shift with patches.
