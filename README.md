# KBE Services — concept website

A single-page concept site for **KBE Services LLC**, an owner-run concrete contractor in
Brookshire / the Katy area, TX (5.0★, 38 Google reviews). Built as a pitch preview by
Rashad — not the official KBE Services website.

## The idea
The hero is a **driveway poured in one day**. A job clock runs 7 AM → 7 PM while the
driveway in front of a house is formed, given a base and rebar, poured, screeded and
finished; the sky moves through the day and the house windows light up at dusk. Visitors
pick a finish (broom, stamped, smooth trowel, exposed aggregate) and watch it go on.
It comes from a real review ("They did the prep. And the concrete in one day.") and
KBE's real 7-to-7, seven-day hours.

## Build
- Single `index.html`, inline CSS + vanilla JS, no build step or dependencies.
- All visuals are drawn in code on `<canvas>` (scene, concrete textures, finish swatches).
  Placeholders for KBE's 91 real Google project photos.
- Fonts: Archivo + Inter + Permanent Marker (Google Fonts).
- Marked `noindex, nofollow`; footer labels it a concept preview.
- Estimate form is front-end only — wire up Formspree / Web3Forms before launch.
- `[CONFIRM WITH CLIENT]` tags mark facts to verify (insurance, warranty, finishes
  offered, full service area, years in business, price ranges).
- The "update messages" in the How-we-work section are written examples, labeled as such.

Content is built from public Google reviews and the KBE Facebook page, read October 2026.
