# lilygo-t-display-s3-amoled-library

# LILYGO T-Display S3 AMOLED Plus – KiCad Library

This repository contains a **KiCad** schematic symbol and PCB footprint
for the **LILYGO T-Display S3 AMOLED Plus** module.

## Scope
- ✅ KiCad schematic symbol (library)
- ✅ KiCad PCB footprint (library)
- ✅ Deliverable outputs (PDF / images) for review
- ✅ All work based strictly on **official LILYGO documentation**

## Non-Scope (to avoid misunderstandings)
- ❌ No firmware, no code examples
- ❌ No physical prototyping, no measurements from a real board
- ❌ No “best guess” pinouts — only what is documented officially

## CAD Tool
- **KiCad** (version to be set in this repo — recommended: KiCad 8.x)

## Repository Structure
LICENSE
README.md
CHANGELOG.md

docs/
docs/sources.md
# Sources and References

This document lists all official sources used to create the schematic symbol
and PCB footprint for the LILYGO T-Display S3 AMOLED Plus module.

## Primary Source (Authoritative)
- **LILYGO T-Display S3 AMOLED Plus Datasheet**
  - File: `docs/datasheet/T-Display-S3-AMOLED-Plus.pdf`
  - Used for:
    - Pin map and signal names
    - Connector definitions
    - Electrical references
    - Mechanical dimensions (footprint)

## Secondary Sources
- Official LILYGO reference schematics and pin maps
  - Used to cross-check signal naming and connector orientation

## Design Rule
- No assumptions are made beyond what is explicitly documented
- In case of ambiguity, the issue is documented in `docs/decisions.md`

docs/decisions.md
# Design Decisions and Open Questions

This document tracks design decisions and open questions identified during
the creation of the KiCad symbol and footprint.

## Global Conventions
- Units: millimeters (mm)
- Signal naming follows official LILYGO documentation
- Power nets: 3V3, VBUS, VBAT, GND

## Open Questions
- None at this stage



datasheet/
T-Display-S3-AMOLED-Plus.pdf
references/
(official reference schematics, pin maps, etc.)

cad/
kicad/
symbols/
footprints/
outputs/
pdf/
images/

## References
All symbols and footprints are created using:
- Official datasheets and reference schematics provided by LILYGO
- The module’s documented pin map and reference designs

## How to Use (KiCad)
1. Add the symbol library from: `cad/kicad/symbols/`
2. Add the footprint library from: `cad/kicad/footprints/`
3. Open the outputs for review in: `cad/kicad/outputs/`

## Status
- v0.1.1 — repository structure and official docs added
- Next milestone: extract pinout from official docs and draft the schematic symbol
