# Phase 2 — Layout Plan

Four slides, stacked vertically with CSS scroll-snap. Each slide is a 16:9 viewport (1600×900 reference). White canvas, tiny red "FIVE GUYS" Anton pill top-left of every slide as a constant brand anchor. Chalk-on-blackboard slide number bottom-right. Everything rotated by ±1° where it makes sense — nothing is pixel-grid perfect.

---

## Slide 0 — TITLE

**Visual hero:** The three team photos as a taped-up photo strip, occupying the bottom 55% of the canvas edge-to-edge. Each photo has a thick white instant-print border, slight drop shadow, rotated individually (`-2°`, `+1°`, `-1°`) so they feel physically pinned to the slide rather than grid-aligned. They overlap each other slightly at the edges, like three polaroids someone dropped on a counter.

**Top 45%:** left-aligned, generous left margin.
- Eyebrow: `INSEAD MBA 26D · PROCESS & OPERATIONS MANAGEMENT` in Archivo uppercase, letter-spaced, steel grey.
- Deck title in Anton, massive (around 180px), two lines:
  - `FIVE GUYS ×`
  - `THE TOURNAMENT`
  with "×" in red `#C92027`. This is the visual anchor of the slide.
- Subhead underneath in Archivo regular, chalkboard black: `A sigma-reduction strategy for the European QSR outlier.`
- Authors line in Archivo small: `Freddie Chambers · Andrew Bauer · Navya Pathak · Karim Hafez`
- Delivered-to line: `For John Eckbert · CEO Five Guys UK & Europe` in Permanent Marker, slightly rotated, like a handwritten addressee note.

**Where the eye goes first:** the photo strip — it's human, red, and unexpected in a deck. Then up to the massive "FIVE GUYS ×" headline, then the "For John Eckbert" sharpie note. Three beats.

**Texture details:**
- A single red-and-white checkerboard strip (8 tiles wide, 2 tall) as a divider between the title block and the photo strip. This is the Jerry-Murrell-five-sons Easter egg — mentioned in no text, but there if you count.
- A tiny "Disney Village Paris · 08-04-26" caption in Permanent Marker under the photo strip, slightly rotated, anchoring the photos in time and place.

---

## Slide 1 — REFLECTION × AMBITION

**Visual hero:** The four stats — `294 stores`, `25%`, `22%`, `£0` — rendered in Anton at a massive scale (~220px numbers), laid out as a 2×2 grid occupying the middle 60% of the slide. No chart, no icons, no decoration. The numbers ARE the slide.

Each stat has:
- The big Anton number (red `#C92027` for `294` and `£0`, chalkboard black for the two percentages — alternating reads as a grid, not a wall of red).
- A thin rule line underneath
- A one-line Archivo caption: `UK · France · Spain · Germany` under 294, `10-year sales CAGR` under 25%, `10-year store CAGR` under 22%, `advertising spend` under £0.

**Top strip:**
- Eyebrow `REFLECTION × AMBITION` in Archivo uppercase, letter-spaced, steel grey.
- Headline in Anton, ~90px, chalkboard black: `The operational outlier in European QSR.`
- Subhead in Archivo: `Five Guys runs a model most chains spent decades engineering away — and it's scaling.`

**Bottom strip (below the stats grid):**
- Body line in Archivo italic, centred: `The constraints that make the food great also make the operations hard. No freezers. No timers. No shortcuts. Every burger is a fresh, same-day newsvendor bet.`
- Ambition line in Anton, ~60px, red pill treatment: `Full potential: 870–950 stores. ~3× growth runway.`
- (All monetary values throughout this deck rendered in **€**, not £.)
- Footer open-loop, bottom-right, Permanent Marker on a rotated sharpie-tape rectangle, ~18px:
  > *"We spent six hours on the floor at Disney Village Paris looking for the bottleneck. We didn't find it in the kitchen."*

**Where the eye goes first:** the 2×2 stats grid. Then up to the "operational outlier" headline, then down to the ambition pill, then the sharpie footer. The footer is the tease that makes you want to scroll to slide 2.

**Texture details:** white canvas, no photos, no backgrounds. The only visual weight is the Anton numbers. This slide's authority comes from restraint — four numbers, nothing else. The deliberate contrast with the chaos of slide 2.

---

## Slide 2 — THE CHALLENGE · DIAGNOSIS

This is the densest slide. Three distinct visual blocks stacked vertically, each with its own texture.

**Top strip:**
- Eyebrow `THE CHALLENGE · DIAGNOSIS` in Archivo uppercase steel grey.
- Headline in Anton ~80px: `One number runs the store.` / `Nobody on the floor knows how it's made.`
- Subhead in Archivo italic: `Five Guys' waste problem is mathematically optimal given its current forecast accuracy. That's the opportunity.`

**Block 1 — Field note with the whiteboard photo (the hero artifact).**
Left side: kraft-paper till-receipt panel (`#B8855B` fill with torn bottom edge, zig-zag CSS gradient), body in Archivo monospace-feeling:
> `FIELD NOTE · Disney Village Paris · 08-04-26`
>
> Every morning, each store is handed a single forecasted revenue number. Ours was €28,000. Everything downstream — patties, potatoes, lettuce, labour — is a deterministic conversion from that number. It's inherited from upstream. Nobody in the store could interrogate it.

Right side: the whiteboard photo, rotated ~1°, white instant-print border, pinned with a small red marker dot top-left. A Permanent Marker caption with a hand-drawn arrow points at the circled "28 000" on the whiteboard:
> *"There it is. One number. Inherited from upstream."*

**Block 2 — The Frozen hero (the emotional centre of the whole deck).**
Full-width chalkboard panel (`#1A1A1A` fill with subtle chalk-dust SVG noise texture, Cabin Sketch font). This is the single strongest visual in the deck — it gets more real estate than anything else.
- Top label in Cabin Sketch, small: `THE DAY DISNEY LAUNCHED FROZEN`
- Two massive numbers side-by-side:
  - Left: `€40,000` in Anton white, with a thick red chalk strikethrough slash through it
  - Right arrow in Permanent Marker pointing right
  - Right: `€15,000` in Anton white, underlined with a chalky line
- Labels underneath in Cabin Sketch small caps: `FORECAST` and `ACTUAL`
- Below, centred, Permanent Marker on tape: `A full day of fresh prep. Straight in the bin.`

No bar chart. No delta graphic. The chalkboard IS the delta. Visceral, not analytical.

**Block 3 — The newsvendor breakdown (the mathematical punchline).**
Styled as a second chalkboard panel, smaller, narrower, bottom half of the slide. Cabin Sketch maths working, each line rendered as if chalked:
```
Cu  = store closure            = catastrophic
Co  = ~30% COGS on unsold prep = painful but bounded
Cu / (Cu + Co) ≈ 0.99          ← critical ratio
μ   = €28,000                  ← mean daily demand
σ   = ±€7,000                  ← current forecast sigma
Q*  ≈ €50,000 prep             ← rational response at 99% service level
```
Final line rendered in red chalk, full-width, Anton ~50px, all-caps:
**STRUCTURAL 80% OVERSHOOT. EVERY DAY. BY DESIGN.**

**Closing line (bottom-right of slide, bold, full-width red pill):**
`Five Guys can't change Cu. Can't change Co. The only lever is σ.`

**Where the eye goes first:** the whiteboard photo — it's the only photo on the slide and it's circled with a sharpie arrow. Then the field note text next to it. Then the massive Frozen chalkboard. Then the newsvendor working. Then the red closing pill. Five beats, each pulling further into the argument.

---

## Slide 3 — HOPE × SOLUTION

**Top strip:**
- Eyebrow `HOPE × SOLUTION` in Archivo uppercase steel grey.
- Headline in Anton ~90px: `You don't need a better model.` / `You need a tournament.` (second line in red)
- Subhead in Archivo: `Generative AI turns Five Guys' 1m+ labelled store-days into a permanent forecasting capability.`

**The asset — full-width red pill strip.**
Full-width band in red `#C92027` with Anton white text ~100px:
`10 YEARS × 294 STORES = ~1,000,000 LABELLED STORE-DAYS`
Small caption underneath in Archivo italic: `forecast vs. actual, every day, every store.`

**The mechanism — three kitchen-ticket receipts.**
Three kraft-paper receipt panels (`#B8855B`, zig-zag torn bottoms, slight ±1° rotations so they look pinned to a rail). Each one has:
- A red "STAGE N" chalkboard square at the top
- An Anton headline (HUNDREDS OF MODELS / SCORED DAILY / WINNERS DEPLOYED)
- Archivo body in kitchen-ticket monospace feel under each

Stage 1 body lists the feature candidates as a printed-register list: `Disney park attendance · weather · school holidays · hotel occupancy · local events · lagged POS · football fixtures · public holidays · day-of-week · weather forecasts · concert schedules · competitor proximity · …`

Stage 2 body: `Each model makes a prediction. Each one scored against actual revenue at close of business.`

Stage 3 body: `Promote the winners. Retire the losers. Per store, per cluster — different stores learn different winning models. Disney Village weights park attendance. London City weights office workers.`

The three receipts sit in a horizontal row across the middle of the slide, slightly overlapping like tickets clipped to a rail. A thin horizontal red "rail" line runs across them.

**POM mechanism sidebar.** Small peanut-tan (`#D9B382`) panel bottom-left, Archivo small, clearly labelled `POM MECHANISM`:
> This is a sigma-reduction strategy analogous to pre-sales information (Session 07) — a demand-side real option. Same Cu, same Co, same critical ratio. Tighter Q*. Lower expected cost on every single day, not just the tails.

**Impact table.** Small, to the right of the POM sidebar. Styled as a till-receipt printout with dotted separators (CSS `border-bottom: dotted`), not a bordered table:
```
                      TODAY       WITH TOURNAMENT
Forecast σ (daily)    ~€7,000     ~€3,000
Q* at ~99% service    ~€50,400    ~€37,600
Prep overshoot        +80%        +34%
Per-store daily save  —           ~€12,800
```

**Honest risks.** Three small steel-grey bullets, bottom-left, Archivo small, deliberately understated:
- Tail events are thinnest in history → human-in-the-loop override for unusual days
- Requires centralising POS feeds across 294 stores
- Transparency is non-negotiable: every forecast shows drivers and confidence; every manager override feeds back as a training signal

**The prize.** Full-width closing strip, chalkboard `#1A1A1A` fill, Anton white ~120px:
`€12.8K / DAY × 294 STORES × 50% REALISM DISCOUNT = €50–200M OPERATIONAL LEVER. NO CAPEX.`

**CTA.** Bottom-right, Permanent Marker on rotated sharpie-tape rectangle, ~32px:
> *"Start in France. 38 stores. Build the tournament. Scale to 900."*

**Credit footer.** Archivo 10px, steel grey, bottom:
`Freddie Chambers · Andrew Bauer · Navya Pathak · Karim Hafez — INSEAD MBA 26D · Process & Operations Management · P2 2026`

**Where the eye goes first:** the full-width red 1,000,000 strip. Then the three kitchen-ticket receipts. Then the big chalkboard "£50–200m" prize. Then the sharpie CTA. Four beats, each one closing the argument tighter.

---

## Cross-slide consistency rules

- Every slide: tiny red `FIVE GUYS` Anton pill top-left (lockup constant)
- Every slide: slide number bottom-right as white chalk on a small `#1A1A1A` chalkboard square
- Every slide: 1600×900 frame, scroll-snap vertical, no horizontal scroll
- Rotations: anything that should feel physical (photos, sharpie tape, kraft receipts) gets ±1–2° rotation; anything typographic stays straight
- Eyebrow line colour always steel grey Archivo uppercase letter-spaced
- Headlines always Anton
- Handwritten notes always Permanent Marker on a tiny rotated white/tape rectangle
- Chalkboard content always Cabin Sketch or Anton reversed out on `#1A1A1A`
- Body text always Archivo

---

**Approval ask — specifically:**
1. Four slides feels right? (Title, Reflection, Challenge, Solution)
2. Slide 2's "whiteboard photo + Frozen chalkboard + newsvendor chalkboard" three-block structure — does that density work, or should the newsvendor working move to its own slide?
3. Slide 3's three kitchen-ticket receipts horizontally as the tournament visual — happy with that? Or would you rather I sketch it as a single wider kitchen-ticket printout with three sections?
4. Anything I've missed from the copy that needs more visual weight?
