# NBA 2K27 Build Minimums Guide — Attribute Floors by Player Type

The minimum attribute rating each build should hit, derived from the badges worth
running. This is the "how high do I actually need each attribute" reference.

> Cross-reference: `badge-requirements.md` (exact thresholds), `badge-tier-list.md`
> (which badges are worth it). Sources: allthings.how, operationsports, timesaver.gg,
> nba2klab (Aug–Sep 2026).

---

## The 2K27 framework is different from 2K26 — read this first

2K26's build-minimums logic ("build to Gold, boost to HoF" using Tier 1 / Tier 2 /
Shooting boost pools) **no longer applies.** The pools are gone. The new model:

1. **Attribute rating sets the badge tier directly.** Hit the number in
   `badge-requirements.md` for the tier you want — that *is* the tier you get. No
   boost math to plan around.
2. **Plan attribute floors to HoF, not Legend.** Legend is **not** reached by
   attributes anymore — it comes from the **Synergy Fuse system** (+1/+2 mid-game on
   a few chosen badges). So the highest attribute number worth targeting is the
   **HoF threshold**; Legend is earned on the court, on your signature badges.
3. **Cap Breakers** raise your attribute ceilings as your OVR climbs (and are
   previewable in the Builder). They're how you get *past* your base build cap to
   reach the steep HoF numbers on a couple of key attributes.
4. **Badge Tokens are a separate budget** — they limit *how many* badges you equip,
   not your attributes. Minimums here get you *eligible*; tokens decide what you
   actually run (see `badge-tier-list.md`).

**Practical rule:** set a hard **HoF floor** on the 1–2 attributes central to your
role, **Gold** on secondary must-haves, and let cheap paired attributes ride at
their (low) thresholds.

**The floors are targets, not guarantees.** Every build has a fixed attribute-point
budget, so you usually **can't hit every ideal floor at once** — you hit the top
tier on your signature attributes and fall back to the next tier (Gold → Silver →
Bronze) on the rest. Each build below lists ideal floors; the point-center section
has a worked "fallback tiers + priority order" example showing how to decide what to
cut, verified against real nba2klab cap data. For an exact fitted build, the
nba2klab MyPlayer Builder Simulator runs on real 2K27 caps.

---

## Minimum every player should have (regardless of build)

Some floors apply to almost any competitive build, because the badge behind them
helps everyone or the attribute is cheap for what it unlocks:

| Attribute | Floor | Gets you | Why universal |
|-----------|-------|----------|---------------|
| Three-Point Shot | **78** (Gold Set and Fire) | A real jumper | Non-shooters get ignored; 78 is the practical playable floor |
| Pass Accuracy | **65** | Bronze Break Starter / usable passing | Cheap; avoids turnovers on basic passes |
| Speed / Agility | **70+ / 60+** | Silver Flash territory | Movement matters on both ends for every build |
| Vertical | **60** | Cheap rebounding/contest floor | Feeds Crasher/Possession Closer/Rise Up cheaply |
| Steal | **60** (Bronze Interceptor) | Basic on-ball D | Low cost, real defensive value |

Everything below is the *role-specific* stack on top of this floor.

---

## Point Guard (≤ 6'4) — ball-handling playmaker

Core identity: create off the dribble, hit pull-ups, run the offense.

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Lightning Launch (HoF) | **91 Speed With Ball** | first-step burst |
| 🏆 Pace (HoF) | **93 Speed With Ball** | covers Lightning Launch too — one attribute, both |
| 🏆 Handles for Days (Gold→HoF) | **90 → 95 Ball Handle** | 90 is Gold, 95 HoF; stamina badge |
| 🏆 Ankle Assassin (Gold) | **93 Ball Handle** | covered at 95 above |
| 🏆 Arc Cadence (HoF) | **98 Three-Point** | or accept Gold at 91 if points are tight |
| Interceptor (Gold) | 90 Steal | on-ball D |
| Dimer (skip/low) | 50 if run at all | de-prioritized this year |

**Attribute minimums:**

| Attribute | Floor |
|-----------|-------|
| Speed With Ball | **93** (Pace HoF; also maxes Lightning Launch) |
| Ball Handle | **95** (Handles for Days HoF + Ankle Assassin Gold) |
| Three-Point | **91 Gold / 98 HoF** on Arc Cadence |
| Steal | 90 (Gold Interceptor) |
| Pass Accuracy | 65+ (Break Starter / Dimer if used) |

---

## Shooting Guard / Wing (6'5–6'9) — 3-and-D / scorer

Core identity: shoot from deep, defend the perimeter.

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Arc Cadence (HoF) | **98 Three-Point** | Gold at 91 acceptable |
| 🏆 Set and Fire (HoF) | **97 Three-Point** | covered by Arc Cadence 98 |
| 🏆 Challenger (Gold→HoF) | **92 → 98 Perimeter Def** | the perimeter-D anchor |
| 🏆 Interceptor (Gold/HoF) | **90 / 97 Steal** | run high |
| Pick Dodger (Gold) | 90 Perimeter Def + 88 Agility | on-ball lockdown |
| Immovable Enforcer (Gold) | 84 Perimeter Def + 85 Strength | strength resistance |
| Posterizer (Gold) | 93 Driving Dunk + 80 Vertical | if athletic finisher |

**Attribute minimums:**

| Attribute | Floor |
|-----------|-------|
| Three-Point | **91 Gold / 98 HoF** (Arc Cadence + Set and Fire) |
| Perimeter Defense | **92 Gold / 98 HoF** (Challenger; feeds Pick Dodger, Immovable Enforcer) |
| Steal | 90 (Gold Interceptor) |
| Agility | 88 (Pick Dodger Gold) |
| Strength | 85 (Immovable Enforcer Gold) — cheap, feeds a badge |

Note how **Perimeter Defense stacks** — 92+ feeds Challenger, Pick Dodger, and
Immovable Enforcer at once. One attribute, three badges.

---

## Lockdown Defender (6'5–6'9) — perimeter stopper

Core identity: shut down the opposing guard/wing.

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Challenger (HoF) | **98 Perimeter Def** | |
| 🏆 Interceptor (HoF) | **97 Steal** | |
| 🏆 Pick Dodger (HoF) | **97 Perimeter Def + 91 Agility** | |
| 🏆 Seatbelt (Gold→HoF) | **91 → 99 Perimeter Def + 80 → 86 Agility** | body-up D |
| Immovable Enforcer (HoF) | 91 Perimeter Def + 92 Strength | |
| Bruiser (Gold) | 93 Strength | stamina drain |
| Ankle Braces (Gold, situational) | 93 Perimeter Def + 89 Agility | keep low |

**Attribute minimums:**

| Attribute | Floor |
|-----------|-------|
| Perimeter Defense | **98–99** (nearly every D badge; the one attribute to max) |
| Agility | **91** (Pick Dodger HoF) |
| Steal | **97** (Interceptor HoF) |
| Strength | **92** (Immovable Enforcer HoF) or 93 for Bruiser Gold |
| Three-Point | **60 floor** to be playable on offense (Bronze); more if two-way |

This build sinks almost everything into Perimeter Defense + Agility. It only works
if you accept a minimal offensive floor — 60 3PT just to not be a zero on that end.

---

## Slasher / Finisher (6'5–6'10) — attack the rim

Core identity: drive, dunk, finish through contact.

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Posterizer (HoF) | **99 Driving Dunk + 90 Vertical** | contact dunks are meta |
| 🏆 Layup Mixmaster (Gold→HoF) | **90 → 99 Driving Layup** | dynamic layup system |
| Float Game (Gold, situational) | 90 Close Shot or 93 Driving Layup | if floaters used |
| Aerial Wizard (skip) | — | driven by dunk rating anyway |
| Paint Prodigy (Gold) | 90 Close Shot | inside scoring |

**Attribute minimums:**

| Attribute | Floor |
|-----------|-------|
| Driving Dunk | **93 Gold / 99 HoF** (Posterizer) |
| Vertical | **80 Gold / 90 HoF** (Posterizer) |
| Driving Layup | **90 Gold / 99 HoF** (Layup Mixmaster) |
| Close Shot | 90 (Paint Prodigy / Float Game Gold) |

---

## 6'10 Point Forward (hybrid) — playmaking big

Core identity: run the offense from a 6'10 frame — handle, pass, shoot, but with a
big's finishing and enough rim presence to matter. Think point-forward / point-center.

**Badge access at 6'10 (the good news):** you keep almost the entire guard toolkit.
Verified against the height gates — a 6'10 build CAN run:

- **Playmaking:** Ankle Assassin (≤6'10, just makes it), Pace (≤6'10), Handles for
  Days (≤7'0), Lightning Launch (≤6'11), Strong Handle, plus all passing badges
- **Shooting:** Arc Cadence (≤6'11), Deadeye, Limitless Range, Quick Trigger, Set
  and Fire, Smooth Operator
- **Finishing/D you also gain as a big:** Posterizer, Rise Up (≥6'5), Paint
  Patroller (≥6'6), Post Spin Catalyst (≥6'1)

**The only guard badge you lose:** Mini Marksman (≤6'4) — irrelevant, it's a
small-guard mismatch badge you'd never use anyway.

⚠️ **Watch the ≤6'10 cliff:** Ankle Assassin and Pace cap at 6'10 exactly. At **6'11
you lose both** — so if you want those two, 6'10 is the hard ceiling for this build.

### The real constraint: attribute budget, not badge access

A 6'10 frame has a lower total attribute cap than a 6'4 guard, spread across more
needs. You **cannot** max guard skills *and* rim protection — pick a lean:

| Lean | Max these | Accept lower |
|------|-----------|--------------|
| **Offensive point forward** | Ball Handle, 3PT, Driving Dunk/Layup | Block, Interior D, Rebound |
| **Two-way point forward** | Ball Handle, 3PT, Perimeter D | Dunk ceiling, Block |
| **Point center** | Ball Handle, Pass, Rebound, Block | 3PT (settle for Gold), Speed |

### Recommended floors (offensive-lean point forward)

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Handles for Days (Gold→HoF) | **90 → 95 Ball Handle** | + covers Ankle Assassin Gold (93) |
| 🏆 Pace (Gold→HoF) | **88 → 93 Speed With Ball** | + covers Lightning Launch |
| 🏆 Arc Cadence (Gold→HoF) | **91 → 98 Three-Point** | your jumper |
| 🏆 Versatile Visionary (Gold) | **90 Pass Accuracy** | the "point" in point forward |
| 🏆 Posterizer (Gold) | 93 Driving Dunk + 80 Vertical | finish as a big |
| Sync Snatcher (Gold) | 82 Off/Def Rebound | you're 6'10 — grab boards |
| Paint Patroller (Silver/Gold) | 60–77 Int Def + 84–93 Block | some rim presence |
| Break Starter (Gold) | 89 Pass Accuracy | covered by Versatile Visionary if 90 |

**Attribute minimums (offensive lean):**

| Attribute | Floor | Feeds |
|-----------|-------|-------|
| Ball Handle | **93–95** | Handles for Days + Ankle Assassin — non-negotiable for a handler |
| Three-Point | **91 Gold / 98 HoF** | Arc Cadence, Set and Fire, Deadeye |
| Speed With Ball | **88–93** | Pace + Lightning Launch |
| Pass Accuracy | **90** | Versatile Visionary + Break Starter + Dimer |
| Driving Dunk | **93** | Posterizer Gold |
| Vertical | **80** | Posterizer; cheap Rise Up/rebound reqs |
| Off/Def Rebound | **82** | Sync Snatcher Gold |
| Block | **84–93** | Paint Patroller — as high as budget allows |

### Honest tradeoff

The thing that makes this build hard: **Ball Handle in the 90s on a 6'10 frame is
expensive**, and it competes directly with the Block/Interior D a 6'10 would
normally spend on. You'll be a **worse rim protector than a true center** and a
**slightly less shifty handler than a true guard** — that's the cost of the hybrid.
What you get is a matchup problem: a 6'10 who brings the ball up and shoots over
smaller guards. If you find the handle feels weak, the fix is dropping to 6'8–6'9
(still forward height, cheaper handle, but you lose the ≥6'6 big badges and the
paint presence).

---

## 6'10 Point Center (recommended lean) — playmaking anchor

This is the point-forward build that **leans into** the 6'10 frame instead of
fighting it: you keep the handle and passing to run the offense, but spend your big
attribute budget where the height is an advantage — **rebounding, rim protection,
and inside finishing** — and settle for a **Gold-tier jumper** rather than an elite
one. Easier to fund than the offensive lean because you're not paying for a 98 3PT.

### Priorities

Max the big-man core + the playmaking that earns "point." Accept Gold on the shot.

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Sync Snatcher (HoF) | **90 Off/Def Rebound** | best rebounding badge; you're 6'10, own the glass |
| 🏆 Possession Closer (Gold→HoF) | **95 Def Rebound + 67 Vertical** | Def Rebound already near-maxed |
| 🏆 Paint Patroller (Gold→HoF) | **77 Int Def + 93 Block → 84 + 99** | rim protection |
| 🏆 Handles for Days (Gold) | **90 Ball Handle** | the handle to bring it up; +Ankle Assassin needs 93 |
| 🏆 Versatile Visionary (HoF) | **99 Pass Accuracy** | the "point" — run the offense; also covers Bail Out (96) + Break Starter (97) + Dimer |
| 🏆 Rise Up (Gold→HoF) | **90 Standing Dunk + 66 Vert** | primary finish for a non-dunker-athlete big |
| Pogo Stick (Gold) | 80 Vertical | repeat contests/boards — Vertical stacks hard here |
| Paint Prodigy (Gold) | 90 Close Shot | inside scoring |
| Bruiser (Gold) | 93 Strength | stamina drain on D; also feeds Boxout Boss |
| Set and Fire (Gold) | **89 Three-Point** | the settled-for Gold jumper |
| Ankle Assassin (Gold, optional) | 93 Ball Handle | only if you can afford the extra 3 Ball Handle |

### Attribute minimums (point center)

| Attribute | Floor | Feeds |
|-----------|-------|-------|
| Def Rebound | **95–99** | Sync Snatcher (90), Possession Closer (95), Boxout Boss — **stacks 3 badges** |
| Off Rebound | **90** | Sync Snatcher HoF |
| Block | **93 Gold / 99 HoF** | Paint Patroller |
| Interior Defense | **77–84** | Paint Patroller — cheap for the tier |
| Vertical | **80** | Pogo Stick Gold; covers Rise Up (66), Possession Closer (67) — **stacks 4 badges** |
| Standing Dunk | **90** | Rise Up Gold |
| Ball Handle | **90** (95 if Ankle Assassin) | Handles for Days |
| Pass Accuracy | **99** | Versatile Visionary — one attribute covers 4 passing badges |
| Three-Point | **89** | Set and Fire Gold — the deliberate Gold jumper |
| Close Shot | 90 | Paint Prodigy |
| Strength | 93 | Bruiser + Boxout Boss |

### Why this lean works at 6'10

- **Two attributes do enormous work.** 95+ **Def Rebound** feeds Sync Snatcher,
  Possession Closer, and Boxout Boss. **80 Vertical** feeds Pogo Stick, Rise Up, and
  Possession Closer. That efficiency is what frees up points for the handle.
- **99 Pass Accuracy** is cheap relative to its value — one attribute unlocks
  Versatile Visionary, Bail Out, Break Starter, and Dimer, making you a genuine
  offensive hub.
- **Ball Handle 90 (Gold Handles for Days)** is the minimum that lets you actually
  bring the ball up without it being a liability. That's the one "guard tax" you
  pay — and it's far cheaper than the offensive lean's 95 + 98 3PT.
- You give up **Pace/Lightning Launch at their high tiers and an elite 3-ball** —
  you're a *half-court* point center, not a run-and-gun guard. Playmake in the
  half court, finish and rebound as a big.

### The one thing to decide

**Ankle Assassin (93 Ball Handle) vs. staying at 90.** The jump from 90 → 93 Ball
Handle on a 6'10 frame is real points that could instead go to Block or Def
Rebound. Skip it unless breaking ankles off the bounce is core to how you want to
play — a point center's value is passing and finishing, not iso handles.

### ⚠️ Reality check — the ideal floors above don't all fit at once

The floors listed for each build are **the number to hit for that tier IF you can
afford it**. You cannot afford all of them on one build — NBA 2K has a fixed
attribute-point budget per height/weight/wingspan. The right way to read this doc:
**hit the HoF/Gold floor on your 1–2 signature attributes, and drop to the next
tier's number (Silver, even Bronze) on everything else.** A Silver badge is not a
failure — it's the realistic outcome for secondary attributes.

Verified against nba2klab's recommended center builds (their Attribute Cap Tool,
real 2K27 cap data). Note how even elite builds land mostly on **Silver/Gold**, not
HoF, once the budget is spread:

**"Triple-Double Threat" — 7'2 playmaking scorer** (the closest real build to a
point center):

| Attribute | Actual | Badge tier it yields |
|-----------|-------:|----------------------|
| Pass Accuracy | 89 | **Gold** Break Starter, Gold Dimer, Silver Versatile Visionary |
| Def Rebound | 87 | **Gold** Sync Snatcher (with 82 Off Reb) |
| Standing Dunk | 90 | Gold Rise Up, Gold Aerial Wizard |
| Mid-Range | 91 | Gold Post Fade Phenom, Gold Static Middy |
| Three-Point | 89 | Gold Set and Fire, Silver Limitless |
| Block | 84 | **Silver** Paint Patroller (not Gold — budget ran out) |
| Interior Def | 78 | Silver Off-Ball Pest |
| Ball Handle | 46 | none — this build gave up handles entirely |
| Vertical | 78 | Silver Pogo Stick, Silver Possession Closer |

The lesson in one line: this 7'2 sacrificed **Ball Handle (46)** completely to fund
scoring + passing + rebounding, and still only reached **Silver** on its defensive
badges. A true point center that *keeps* a 90 Ball Handle will have to drop
something else (likely Block or the jumper) even further.

### Three complete verified center builds (nba2klab, full attribute spreads)

These are real, cap-accurate builds with every attribute confirmed — not floors.
The **Rise & Dime** is the closest to a playmaking point-center identity; the
**2-Way Bucket Chaser is a 6'11**, one inch off your target 6'10.

| Attribute | Triple-Double Threat (7'2) | Rise & Dime Paint Protector (7'1) | 2-Way Bucket Chaser (6'11) |
|-----------|:--:|:--:|:--:|
| Close Shot | 90 | 75 | 90 |
| Driving Layup | 60 | 55 | 85 |
| Driving Dunk | 70 | 75 | 75 |
| Standing Dunk | 90 | 90 | 65 |
| Post Control | 91 | 90 | 89 |
| Mid-Range | 91 | 53 | 89 |
| Three-Point | 89 | 68 | 94 |
| Free Throw | 76 | 78 | 91 |
| **Pass Accuracy** | 89 | **89** | 76 |
| **Ball Handle** | 46 | 49 | 65 |
| Speed w/ Ball | 40 | 32 | 75 |
| Interior Def | 78 | 85 | 68 |
| Perimeter Def | 35 | 62 | 85 |
| Steal | 33 | 60 | 71 |
| Block | 84 | 88 | 60 |
| Off Rebound | 82 | 88 | 80 |
| **Def Rebound** | 87 | **94** | 50 |
| Speed | 65 | 67 | 79 |
| Agility | 50 | 54 | 73 |
| Strength | 83 | 83 | 73 |
| Vertical | 78 | 80 | 80 |
| Weight / Wingspan | 227 / 7'2 | 237 / 7'7 | 210 / 6'11 |
| **Badges unlocked** | 34/53 (13G/17S/4B) | 29/53 (**1 HoF**/8G/10S/10B) | 42/53 (11G/15S/16B) |

**How to read these for your 6'10 point center:**
- **Rise & Dime (7'1)** is the template to copy: 89 Pass, 94 Def Reb, 88 Off Reb,
  88 Block, 85 Int Def — it hits the **only HoF badge of the three (Sync Snatcher,
  94/92 reb)** and Gold Break Starter/Dimer/High-Flying Denier. It trades away the
  jumper (68 3PT) and handle (49) to get there. This is the "playmaking rim-running
  anchor" build.
- **2-Way Bucket Chaser (6'11)** is the closest *height* and shows the opposite
  trade: it keeps a 65 Ball Handle and 94 3PT (Gold Arc Cadence + Set and Fire) but
  drops rebounding to 50 Def Reb. This is the "stretch/handle" point center.
- **You can't have both.** At 6'10–7'1 the budget forces a choice between
  *elite rebounding+defense* (Rise & Dime) and *handle+shooting* (Bucket Chaser).
  A point center leans Rise & Dime and buys back a little handle with cap breakers.
- **Cap-breaker path (from nba2klab):** first 5 into Off Reb, next 3 Def Reb, next 5
  Block, next 5 Driving Dunk — then personal preference. That's how a big pushes
  Silver badges toward Gold after the base build.

### Target build: rebounder + finisher + defense + passing + 86 Mid

This is the specific spec — elite rebounding, real Driving Dunk, the defense you
need, passing, and **86+ Mid-Range** for jumper access. **No single verified build
hits all five at once** — it's a genuine budget conflict (86 Mid competes directly
with the reb/defense points). The closest verified base is the gamesfuze
**All-Rounder (7'0)**; the column below adapts it to hit your 86 Mid via a cap
breaker, showing what you trade.

| Attribute | Gamesfuze All-Rounder (7'0, verified) | Your target (adapted) | Why |
|-----------|:--:|:--:|-----|
| Off Rebound | 93 | 90 | elite reb — Gold Sync/Crasher |
| Def Rebound | 94 | 92 | elite reb — HoF/Gold Sync Snatcher |
| Driving Dunk | 75 | **80** | real finishing (Uber Athletic Tomahawks at 90 if capped) |
| Standing Dunk | 75 | 80 | Silver→Gold Rise Up / bigman contact via caps |
| Block | 84 | 84 | Silver Paint Patroller |
| Interior Def | 74 | 78 | Silver Off-Ball Pest / Post Lockdown |
| Pass Accuracy | 90 | 89 | Gold Break Starter + Dimer |
| **Mid-Range** | 80 | **86** | **your jumper-access target** — Static Middy, better bases |
| Three-Point | 90 | 78 | drop to Silver Set and Fire to fund Mid + reb |
| Ball Handle | 55 | 55 | enough to bring it up, not iso |
| Vertical | 80 | 80 | Gold Pogo; feeds dunk + reb + block |
| Strength | 94 | 90 | Brick Wall / boxout |
| Speed / Agility | 64 / 50 | 64 / 50 | fine for a paint big |
| Weight / Wingspan | 270 / 7'6 | ~250 / 7'4–7'6 | keep wingspan long for reb/block |

**The trade you're making:** to reach **86 Mid-Range** while keeping elite
rebounding + defense + passing, the points come out of **Three-Point** (90 → 78,
still Silver Set and Fire) and a little **Strength**. You keep a genuine jumper (86
Mid unlocks the mid-gated bases like the LaMelo-style shots), elite boards, Gold
passing, and 80 Driving/Standing Dunk for finishing.

**On the jumper (86 Mid is the right call):** many strong bases are **mid-range
gated**, not 3PT gated — an 86 Mid / 82 3PT unlocks the accessible high-window bases
(e.g. LaMelo-style) that a low-mid build can't equip. That's why 86 Mid "makes more
shots" than chasing 3PT alone. See `jumpshot-guide.md` → low-3PT / mid-gated section.

**Cap-breaker order for THIS build:** Off Reb → Def Reb → Block → Driving Dunk
(nba2klab's big-man order) — pushes your Silver reb/defense badges toward Gold and
Driving Dunk toward the 90 Uber Athletic Tomahawk finish after the base is set.

> Ground the exact 6'10 numbers in nba2klab's free MyPlayer Builder Simulator — set
> 6'10, long wingspan, and confirm 86 Mid + 92 Def Reb both fit the cap before
> locking. The base is verified (gamesfuze All-Rounder); the 86-Mid adaptation is the
> documented trade, not a fabricated fit.

**Fallback tiers for the point center — what to accept when the budget bites:**

| Attribute | Ideal (HoF/Gold) | Acceptable fallback | Floor (still worth it) |
|-----------|------------------|---------------------|------------------------|
| Ball Handle | 90 (Gold HFD) | 81 (Silver HFD) | 71 (Bronze — can still bring it up) |
| Pass Accuracy | 99 (HoF VV) | 89 (Gold Break Starter/Dimer) | 80 (Silver VV) |
| Def Rebound | 90 (HoF Sync) | 82 (Gold Sync) | 70 (Silver Sync) |
| Block | 93 (Gold Paint Patroller) | 84 (Silver PP) | 70 (Bronze PP) |
| Vertical | 80 (Gold Pogo) | 70 (Silver Pogo) | 63 (Bronze Pogo) |
| Standing Dunk | 90 (Gold Rise Up) | 81 (Silver) | 60 (Bronze) |
| Three-Point | 89 (Gold Set and Fire) | 78 (Silver) | 60 (Bronze — playable floor) |

**Priority order when cutting** (keep the top, sacrifice from the bottom):
1. Pass Accuracy — the whole point of "point" center; keep at 89+ (Gold)
2. Def Rebound + Vertical — cheap, stack many badges; keep Gold
3. Ball Handle — 90 if fundable, else 81 Silver (still lets you handle)
4. Block — accept Silver (84) if needed; Triple-Double Threat proves that's normal
5. Three-Point — first to drop to Silver (78) or even Bronze; you're not a shooter

> **Want an exact, fully-fitted build?** nba2klab's free MyPlayer Builder Simulator
> (nba2klab.com/myplayer-builder) runs on real 2K27 cap data — set height 6'10,
> pick weight/wingspan, and it shows every cap and which badge tier each unlocks.
> Use it to lock the final numbers; this doc gives you the priorities to feed it.

---

## Center / Big Man (6'10+) — rim protector / rebounder
Core identity: protect the paint, rebound, finish inside.

| Badge (target) | Attribute floor | Notes |
|----------------|-----------------|-------|
| 🏆 Paint Patroller (Gold→HoF) | **77 Int Def + 93 Block → 84 Int Def + 99 Block** | rim protection |
| 🏆 Sync Snatcher (Gold→HoF) | **82 → 90 Off/Def Rebound** | best rebounding badge |
| 🏆 Posterizer (Gold+) | 93 Driving Dunk + 80 Vertical | if lob threat |
| 🏆 Rise Up (Gold→HoF) | **90 Standing Dunk + 66 Vertical → 99 SD + 70 Vert** | standing finishes |
| 🏆 Pogo Stick (Gold→HoF) | **80 → 90 Vertical** | repeat contests |
| Paint Prodigy (Gold) | 90 Close Shot | inside scoring |
| Possession Closer (Gold) | 95 Def Rebound + 67 Vertical | elite D-boarding |
| Break Starter (Gold) | 89 Pass Accuracy | outlet passing, valuable in 5v5 |
| Bruiser (Gold) | 93 Strength | stamina drain |

**Attribute minimums:**

| Attribute | Floor |
|-----------|-------|
| Block | **93 Gold / 99 HoF** (Paint Patroller) |
| Interior Defense | **77 Gold / 84 HoF** (Paint Patroller) — cheap for what it gives |
| Def Rebound | **90–95** (Sync Snatcher HoF at 90; Possession Closer Gold at 95) |
| Off Rebound | **90** (Sync Snatcher HoF) |
| Vertical | **90** (Pogo Stick HoF; also covers Rise Up 70, Crasher/Possession Closer 70) |
| Standing Dunk | **90 Gold / 99 HoF** (Rise Up) |
| Close Shot | 90 (Paint Prodigy Gold) |
| Strength | 93 (Bruiser Gold) |

Vertical does huge work here — **90 Vertical** simultaneously maxes Pogo Stick and
clears the (cheap, ~70) Vertical requirements on Rise Up, Crasher, and Possession
Closer. Prioritize it.

---

## Attribute floors at a glance

| Build | Attr 1 | Attr 2 | Attr 3 | Attr 4 |
|-------|--------|--------|--------|--------|
| **Point Guard** | 93 Speed w/ Ball | 95 Ball Handle | 91–98 3PT | 90 Steal |
| **3-and-D Wing** | 91–98 3PT | 92–98 Perimeter D | 90 Steal | 88 Agility |
| **Lockdown** | 98 Perimeter D | 91 Agility | 97 Steal | 92 Strength |
| **Slasher** | 93–99 Driving Dunk | 80–90 Vertical | 90–99 Driving Layup | 90 Close Shot |
| **6'10 Point Forward** | 93–95 Ball Handle | 91–98 3PT | 88–93 Speed w/Ball | 90 Pass Acc |
| **6'10 Point Center** | 95–99 Def Rebound | 99 Pass Acc | 93–99 Block | 90 Ball Handle |
| **Center** | 93–99 Block | 90 Def Rebound | 90 Vertical | 90–99 Standing Dunk |

---

## Key principles for 2K27

1. **Attribute = tier, directly.** No boost pools. The number in the requirements
   doc is the tier you get. Plan floors to **HoF** on your 1–2 signature attributes.
2. **Legend comes from Synergy, not attributes.** Don't chase Legend attribute
   numbers — they don't exist. Fuse your signature badge for the mid-game boost.
3. **Cap Breakers unlock the HoF numbers.** The steep HoF thresholds (98 3PT, 99
   Block) usually need Cap Breakers on top of your base build cap. Preview them in
   the Builder.
4. **Stack one attribute across badges.** Perimeter Defense feeds 3–4 defensive
   badges; Vertical feeds four big-man badges; Ball Handle feeds two guard badges.
   Every point does double duty.
5. **Tokens limit quantity, attributes limit tier.** These floors make badges
   *eligible*. You still can't run everything — spend tokens on the S-tier core
   (see `badge-tier-list.md`) and let cheaper badges sit lower.
6. **Set a minimum offensive floor even on defenders** — 60 3PT keeps a lockdown
   from being unguardable-ignorable on offense.

> **Confidence note:** 2K27 launched Sep 4, 2026; the meta is still early. Thresholds
> are from published requirement data, but the "which floors are worth it" judgments
> will firm up after the first gameplay patches.
