# Hydroponic Succulent Planter for a Glass Tumbler

A two-part 3D-printed insert that lets you grow succulents **hydroponically** inside
an ordinary glass tumbler. The roots stay submerged; the plants sit above the water
line on a perforated top plate.

Designed for a tumbler with a slanted cut rim, but the parts drop into any glass
with an inner mouth diameter of **90 mm or more**.

## Preview

[`viewer/index.html`](viewer/index.html) is an interactive 3D view of both parts on a
scaled print bed. Enable GitHub Pages for this repo (Settings → Pages → Source: main,
folder `/`) and it becomes browsable at `/viewer/`. Opened straight off disk the
browser blocks local file reads — drag the `.stl` files onto the canvas instead.

## Parts

| File | Size | Weight (PETG, solid) | Print orientation |
|---|---|---|---|
| `stl/top-plate.stl` | 84 × 84 × 4.9 mm | 13.9 g | flat, as exported |
| `stl/mesh-base.stl` | 91.2 × 91.2 × 73 mm | 48.9 g | upright, as exported |

Both files are watertight, single-body, and already in the correct print
orientation. **No supports needed.**

**Top plate** — Ø84 disc, 3 mm thick, with a gently domed surface. Four Ø26
planting holes on a 23 mm radius, four decorative cut-outs (heart, star, flower,
balloon) on a 32 mm radius, and a Ø12 centre hole for topping up water.

**Mesh base** — a tapered skirt going from Ø76 at the top down to Ø60 at the foot,
67 mm tall, 3 mm walls, pierced by 43 randomly scattered cut-outs including a
capybara. It self-centres on the curved bottom of the glass. Three Ø4 holes around
the foot let you thread a line through to tie down a weight.

The top plate drops into the neck of the base with 0.5 mm of clearance per side.

## Print settings

Printed on an Elegoo Neptune 4, 0.4 mm nozzle.

| | |
|---|---|
| Material | **PETG** — PLA hydrolyses and turns brittle in permanent water contact |
| Nozzle | 240 °C |
| Bed | 80 °C |
| Layer height | 0.2 mm |
| Perimeters | 4 |
| Infill | 25 % gyroid |
| Brim | 5 mm for the mesh base; none needed for the top plate |
| Supports | **None** |

## Assembly and use

1. Rinse all soil off the root balls — required for hydroponics, and it shrinks the
   root ball enough to fit the holes.
2. Drop the mesh base into the glass, then seat the top plate in its neck.
3. Fill with water plus hydroponic nutrient, up to just below the top plate.
4. Set the plants into the Ø26 holes. Small plants and leaf cuttings will fall
   through — use a net pot or pack moss around the collar.
5. Optional: an aquarium air stone in the base keeps the water oxygenated, which
   the roots need.

Change the water every few days; nutrient concentrates as water evaporates.

## Notes

- The Ø26 holes are sized for a **root ball**, not for individual roots. This is
  the single most important dimension in the design.
- A Ø84 disc fits at most five Ø26 holes — pure geometry. Six plants need a
  multi-tier design.
- Printed unsupported, the top of each round hole sags slightly. It is cosmetic and
  does not affect function.

## Licence

[CC BY-NC-SA 4.0](LICENSE) — share and remix freely for non-commercial use, credit
the author, share alike.
