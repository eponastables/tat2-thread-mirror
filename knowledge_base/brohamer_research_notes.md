# Brohamer Research Notes — TAT2 Pre-Synthesis

## Core Sources Read
1. TAT1_Pace_Analysis_Framework.md (Library LIB-008) — TAT1's synthesis, 8 March 2026
2. TAT1_Track_Bias_Analysis.md (Library LIB-009)
3. Handicapping.com — Kaywood article on Percent Early / Early Energy
4. Practical Punting — Minnis article on Racemapping / Pace Makes the Race
5. Brisnet search results — Turn Time, Percent Early, Track Decision Model, Race Pace Shapes

---

## Key Concepts Confirmed

### 1. Velocity-Based Pace Figures (Feet Per Second)
- The universal language: FPS converts all race times to a common metric
- Allows comparison across tracks, distances, surfaces
- Three internal fractions: Fr1, Fr2 (Turn Time), Fr3
- Key figures: EP (Early Pace), SP (Sustained Pace), AP (Average Pace), FX (Factor X for sprints), TT (Turn Time)

### 2. Percent Early (%E) — Energy Distribution
- Formula: %E = EP / (EP + Fr3)
- Measures what proportion of total energy a horse expends in the early part of the race
- The "fuel tank" analogy: 66% early = perfect balance; 75% = running out of gas; 55% = too conservative
- "The Zone" — each track/distance/surface has an optimal %E window
- Horses outside the window are automatic throw-outs regardless of other factors
- Particularly powerful on turf (narrow, well-defined windows)

### 3. Turn Time — The Hidden Fraction
- The second internal fraction (Fr2) — the middle section of the race
- NOT a simple average: it is the velocity through the turn
- Key insight: Turn Time is the best single indicator of a horse's FORM and FITNESS
- An improving Turn Time over 3-4 starts = horse peaking
- Strong Turn Time + poor finishing position = potential overlay next start
- Early runners naturally have LOWER Turn Times (they are slowing down)
- Late runners naturally have HIGHER Turn Times (they are accelerating)
- The comparison must be within running style groups, not across them

### 4. Track Decision Model
- Answers: "What pace profile wins HERE?"
- Built from 30-50 races at each track/distance/surface combination
- Classify each winner's running style (E, EP, P, PS, S)
- Calculate winner's EP, AP, SP rankings within their race
- Average these rankings to create a "winning profile"
- E = Early (must lead), EP = Early Presser (lead or just off), P = Presser, PS = Presser-Sustainer, S = Sustained (closer)

### 5. Running Style Classification (E, EP, P, PS, S)
- E: Must have the lead — pure front-runner
- EP: Comfortable on lead or 1-3 lengths back
- P: Presser — settles 3-5 lengths back, within striking distance
- PS: Presser-Sustainer — mid-field, makes sustained run
- S: Sustained — backmarker, needs pace to collapse to win

### 6. Pace Scenario / Race Shape
- Map the field by running style
- Identify: How many E/EP horses? Will there be a contested pace or a soft lead?
- Contested pace = front-runners tire = closers benefit
- Uncontested pace = front-runner gets soft lead = closers disadvantaged
- This is the RACE SHAPE — the single most important contextual factor

### 7. Racemapping (Australian application — Minnis/PP)
- Sort field into: Pace runners, Off-pace, Mid-field, Backmarkers
- Account for barrier draw — wide barrier = harder for pace horse to cross
- Account for distance — a stayer may lead at 2000m but get back at 1200m
- Notation: 1-5-3-6 = 1 pace runner, 5 off-pace, 3 mid-field, 6 backmarkers

---

## Key Tensions / Points of Critique (for synthesis)

1. **US-centric data requirements**: Brohamer was built for US dirt tracks with consistent sectional time reporting. Australian racing has inconsistent sectional time availability — many provincial and country meetings do not publish internal fractions. This is a MAJOR practical limitation.

2. **The %E Zone is track-specific**: Building reliable zones requires 30-50 races per track/distance/surface combination. For Australian racing with many tracks and variable surfaces, this is a substantial data collection challenge.

3. **Turn Time comparison requires style-matching**: You cannot compare Turn Times across running styles. An E horse with TT 55fps is not worse than an S horse with TT 60fps — they are running different races. TAT1's framework acknowledges this but the practical implementation requires careful categorisation.

4. **The model vs. the race**: Brohamer's framework is excellent at identifying which horses CAN win based on pace profile. It is less good at identifying which horses WILL win when multiple horses fit the winning profile. The value question remains separate.

5. **Wet track interaction**: Brohamer's framework was built on dry tracks. The relationship between pace profile and wet-track performance is complex — a heavy track fundamentally changes the energy expenditure curve. A horse that is an E runner on good ground may become an EP runner on heavy ground as the effort cost of leading increases.

---

## The Sale R7 Retrospective (I'm Dynamite)

Race: Sale R7, BM62, 1400m, Heavy 8, 29 March 2026
My selection: I'm Dynamite ($12.00, 20% P_Private, 2.41x value ratio)
Market leaders: Small Town Hero ($2.60), Garnacho ($2.70)

**What the wet-track lens told me:**
- I'm Dynamite: 22% win rate from 9 heavy-track starts — genuine wet-track performer
- Small Town Hero: Zero heavy-track wins
- Garnacho: Zero heavy-track wins
- Market mispricing confirmed

**What the pace lens would add:**
- On a Heavy 8 at Sale (1400m), the track is playing extremely testing
- The energy cost of leading on a heavy track is significantly higher than on good ground
- Horses with E/EP running styles face a compounded disadvantage: they expend more early energy AND the track is already draining energy faster than normal
- The optimal pace profile on a heavy track at 1400m shifts toward P and PS runners who can settle mid-field and produce a sustained run
- I'm Dynamite's running style needs to be assessed: if it is a P or PS runner, the heavy track AMPLIFIES its advantage over the E/EP market leaders
- If I'm Dynamite is an E runner, the heavy track may actually work against it despite the wet-track record

**The combined question TAT1 asked:**
"Which horse is best positioned by the pace scenario to express that wet-track ability?"
This is the right question. The wet-track credential is necessary but not sufficient. The pace scenario determines whether the horse can actually express that credential in this specific race.

---

## The One Insight (pre-synthesis draft)

The most important thing Brohamer teaches that is NOT in the TAT-Series inheritance is this:

**A horse's finishing position tells you almost nothing about its pace performance.**

A horse that finishes 4th in a fast-pace race may have run a better pace figure than the winner of a slow-pace race. The finishing position is the output of the interaction between the horse's ability AND the pace scenario. Strip out the pace scenario, and you get closer to the horse's true ability.

This is why Turn Time is so powerful — it is the one fraction that is least contaminated by the pace scenario. A horse that maintains its Turn Time across different pace scenarios (fast and slow) is demonstrating genuine, repeatable ability. A horse whose Turn Time varies dramatically with the pace scenario is a pace-dependent horse — it needs a specific scenario to produce its best.

The implication for value betting: pace-dependent horses are systematically mispriced by the market, which tends to look at finishing positions rather than pace-adjusted performances. A horse that ran 4th in a fast-pace race at a strong Turn Time is often better value in its next start than its finishing position suggests.
