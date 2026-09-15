# Bonsai Courtyard Light Study

An interactive 3D viewer for one courtyard bonsai lighting study. Open the
site, not this repository:

**https://rfpchua.github.io/bonsai-courtyard-light-study/**

Four candidate fixture layouts over the same accepted courtyard scene
(`c04-balcony-300-v1`): the incumbent arrangement, and three alternatives
found by re-aiming and repositioning the *same eleven fittings*. The layout
selector switches between them; the overhang selector makes the balcony slab
translucent so you can see whether each fitting actually sits over it.

## What you are looking at

| | |
|---|---|
| Scene | Accepted reconstruction of the courtyard, unchanged |
| Tree | Surveyed *Podocarpus macrophyllus*, 62,246 retained foliage samples |
| Fittings | 5 overhead Philips UniFlood M G2 + 6 Targetti DART Medium pole heads |
| Schedule | 11.5 electric hours/day |
| Metric | DLI, mol m⁻² day⁻¹, over the foliage samples |

## What this is not

- **Not an accepted design.** These are experiment outputs. Nothing here is
  selected, ordered, approved or scheduled.
- **No mounting is qualified.** Bracket, fixing, substrate, sweep and
  service-access design are all unresolved. Every geometry result in the
  viewer is a proxy screen, not a mounting design.
- **The 120 W and 150 W photometry is a lumen-scaled 80 W surrogate.** No
  exact high-power IES file is held.
- **No DLI figure here is a validated retention or injury boundary** for this
  species. The 4, 6 and 8 DLI marks are descriptive only.
- **No global optimum is claimed.** The search ran under a declared compute
  budget and stopping rule.

The decision report, the cost tables and the supplier quotes are not published
here.

## Contents

A static bundle: one page, the viewer scripts, `three.js` r158, the bonsai
mesh, and one data file per layout. No build step and no server.
