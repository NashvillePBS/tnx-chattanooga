# Print specs — Crossroads Guide brochure (Memphis)

For the local printer. Files in `brochure/out/` (regenerate with
`python3 brochure/build_brochure.py`).

## Files

| File | What |
|---|---|
| `front.tif` | Map side — CMYK TIFF, 300 dpi |
| `back.tif` | Panel side (cover, welcome, listings) — CMYK TIFF, 300 dpi |
| `front-proof.png`, `back-proof.png` | RGB proofs at 25% with trim (magenta box) and fold guides (dashes) — **not for production** |

## Dimensions

- **Trim size:** 24 × 18 in flat
- **Bleed:** 0.125 in on all sides (files are 24.25 × 18.25 in / 7275 × 5475 px)
- **No printer's marks in the files** — trim/fold per this spec
- **Fold:** map fold — vertical accordion at 4-in intervals (5 vertical folds),
  then one horizontal half fold → finished piece 4 × 9 in.
  The **cover panel** is the bottom-right panel of the back side; the panel
  grid on the back is 6 columns × 2 rows of 4 × 9 in.

## Color

- CMYK, no ICC profile embedded — printer should treat as US commercial
  defaults (SWOP/GRACoL) and proof against the supplied PNGs for intent
- Brand colors to hold: show blue ≈ C82 M69 Y0 K46 (#314289),
  show red ≈ C0 M71 Y68 K32 (#AE3238)
- Logos are embedded raster at 300 dpi. Vector originals available on request:
  Tennessee Crossroads logo + Nashville PBS horizontal white (on PBS-Blue
  #2638C4 chip) — supplied as SVG/AI by Nashville PBS if the printer prefers
  to re-place them.

## Stock suggestion

Classic road-map feel: 60–80 lb text, uncoated or matte, tolerant of
repeated folding. Final stock choice is the printer's call with Shane.

## Content notes

- Map data © OpenStreetMap contributors — attribution is printed on the map
  side and must remain.
- No funder credits appear anywhere on this piece (intentional).
- Host names ARE included on this piece (intentional; the web/home-print
  itinerary differs).
