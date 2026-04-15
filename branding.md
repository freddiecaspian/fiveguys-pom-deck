# Five Guys Pitch Deck — Branding Direction

Audience: John Eckbert, CEO Five Guys UK & Europe
Deck: INSEAD POM final — Process & Operations Management, P2 2026
Authors: Freddie Chambers · Andrew Bauer · Navya Pathak · Karim Hafez

The brief for this brand system: **it should feel closer to a ticket stub than a Keynote template.** If someone glanced at a slide and thought "consulting deck," we've failed. If they thought "this looks like something taped to a Five Guys wall," we've won.

## 1. Palette

| Role | Hex | Notes |
|---|---|---|
| Primary Red | `#C92027` | Pantone 711 C equivalent. The print-true Five Guys red — slightly blood-toned, not fire-engine. Used for the logo pill, headline accents, the Frozen hero block. |
| White | `#FFFFFF` | Dominant background. Slide canvas. Tile walls. |
| Chalkboard | `#1A1A1A` | Warm near-black. For chalkboard blocks (the newsvendor working on slide 2) and body text. Not pure `#000`. |
| Kraft Paper | `#B8855B` | Bag tone. Used for the "till receipt" panels and the field-note block. |
| Peanut Tan | `#D9B382` | Lighter warm tone. Secondary panel fills, muted callouts. |
| Steel Grey | `#A8ADB3` | Open-kitchen stainless. Honest-risks block, small footnotes. |

Only these six. No gradients, no tints beyond these, no accent colours. If a chart needs a second colour, it's kraft vs red — never blue, never green.

## 2. Typography (committed — not a shortlist)

All Google Fonts, all free.

- **Anton** — big numbers and slide headlines. Condensed block sans, very close to the actual Five Guys wordmark lettering. Used at 120–220px for the stats on slide 1, the £12.8k figure on slide 3, and inside any "FIVE GUYS"-style red pill treatment.
- **Permanent Marker** — the "Five Guys says…" handwritten callouts. Used for: the footer open loop on slide 1 ("We spent six hours on the floor…"), the CTA on slide 3 ("Start in France…"), any pull-quote taped onto the slide like a sharpie wall note.
- **Cabin Sketch** — chalky hand-drawn feel for the chalkboard block on slide 2 (newsvendor working) and the tournament stage labels on slide 3. Reads as chalk-on-slate without being cartoony.
- **Archivo** — body copy, subheads, table data, footnotes. Industrial sans, pairs with Anton without competing.

One font per role, no mixing within a role. If it's a big number, it's Anton. If it's handwritten, it's Permanent Marker. If it's on a chalkboard, it's Cabin Sketch. Everything else is Archivo.

## 3. Texture & mood

Five Guys' visual DNA is **"un-designed-on-purpose."** The walls are cluttered with press pulls, sharpie notes, chalkboards listing which Idaho farm the potatoes came from that morning, sacks of potatoes stacked in the customer area, free peanut barrels. Nothing is art-directed. Everything looks like it was made that morning by someone who works there.

The deck should borrow that language literally:

- **White subway tile** as an occasional background texture — subtle SVG pattern, not a photo. Used behind the "Five Guys says" quote on slide 1.
- **Red-and-white 6-inch checkerboard tile** — used sparingly as a section divider or corner motif. There's a storytellable detail here: five vertical red-tile rows = Jerry Murrell's five sons. One of these lives in the slide 1 hero.
- **Chalkboard panels** — dark `#1A1A1A` backgrounds with Cabin Sketch text, subtle chalk-dust noise (SVG filter, no images). Slide 2's newsvendor maths block IS a chalkboard.
- **Kraft-paper till-receipt panels** — `#B8855B` fill, Courier-like monospace register tape for the field note and impact table. Receipt edge tear can be done in CSS with a zig-zag gradient.
- **Sharpie-on-tape callouts** — Permanent Marker text on a tiny rotated white rectangle, as if a post-it or tape strip was stuck to the slide. Used for the open loop footers and the CTA.

**Texture rule:** no stock photography. Every texture is CSS or inline SVG. If it can't be drawn with fills, borders, gradients, and filters, it doesn't belong in this deck.

**Exception — site visit photos.** Four photos from the Disney Village Paris site visit (08-04-26) are in scope because they are evidence, not decoration:
- Three team shots (team in Five Guys red tees + caps, outside the store, in front of Vapiano, in the kitchen) — live on the **title slide** as a taped-to-wall photo strip, slight ±1° rotations, white instant-print borders.
- One "TABLEAU DES PREPARATIONS" whiteboard photo with the circled forecast ("CHIFFRE D'AFFAIRES PRÉVISIONNEL — 28 000") — lives on slide 2 as the field-note artifact. A Permanent Marker arrow/caption points at the circled number.

No other photography anywhere in the deck.

## 4. The Frozen hero (slide 2)

The £40k forecast / £15k actual example is the emotional centre of the deck. It gets its own treatment: a chalkboard block with the two numbers rendered in Anton at massive scale, `£40,000` struck through in red, `£15,000` chalked underneath. Below it, in Permanent Marker: "A full day of fresh prep. Straight in the bin." No chart, no bar graph — the delta IS the visual. A bar chart would be consulting. A chalkboard working is Five Guys.

## 5. The tournament (slide 3)

Not a funnel (too McKinsey). Not a bracket (too literal). The tournament is a **three-panel till-receipt layout** — three strips of kraft paper, each torn at the bottom, with Anton headlines (STAGE 1 HUNDREDS OF MODELS / STAGE 2 SCORED DAILY / STAGE 3 WINNERS DEPLOYED) and Archivo body under each. Receipts "pinned" with a little red check-mark corner. Feels like three kitchen tickets clipped to a rail.

## 6. Anti-patterns (non-negotiable)

Things this deck MUST NOT become:

- ❌ Stock photography of burgers, chefs, or smiling customers
- ❌ Glassmorphism, pastel gradients, or any "AI startup 2024" aesthetic
- ❌ Corporate slide layouts with title / 3-column / footer grids
- ❌ Sans-serif-on-cream millennial minimalism (Sweetgreen/Shake Shack)
- ❌ Drop shadows, blur effects, parallax, or animation for animation's sake
- ❌ Blue, green, yellow, or any accent colour beyond the six in the palette
- ❌ Rounded friendly fonts, scripts, or handwriting on headlines
- ❌ Bar charts, pie charts, or any dataviz that could appear in a McKinsey slide
- ❌ Icons from a Lucide/Heroicons set — if an icon is needed, it's drawn inline as sharpie doodle
- ❌ White space as design. Five Guys walls are deliberately cluttered — empty space reads wrong here.
- ❌ A Figma-template feel. If it could be mistaken for a SaaS landing page, start over.

## 7. Proof-of-authenticity details

Small things that signal "we understand the brand":

- A tiny red "FIVE GUYS" pill lockup in Anton top-left of each slide, same as their logo
- Slide numbers as chalk on a small blackboard square
- The potato-origin chalkboard ("Today's potatoes from: Rigby, Idaho") lives as an Easter egg — maybe as slide 1's footer corner
- The peanut-shell tan used for a single "free peanut" style callout somewhere in the deck
- Everything slightly imperfect: rotations of ±1°, hand-drawn borders, nothing pixel-grid-aligned

---

**Approval ask:** Does this direction land? Specifically:
1. Palette — happy with the six colours and no accents?
2. The "till receipt + chalkboard + sharpie tape" vocabulary as the three core textures?
3. The Frozen block as a chalkboard-with-struck-through-number (not a bar chart)?
4. The tournament as three kitchen-ticket receipts (not a funnel or bracket)?

Once you approve, I'll write the Phase 2 layout plan for all three slides.
