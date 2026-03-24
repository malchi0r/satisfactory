# Tier 5 - Oil Processing

**Status:** Complete
**Total Time:** ~7h 46m (Sessions 10–13)
**Sessions:** 4

---

## Milestones

- [x] Jetpack — Session 10, 3:09:00
- [x] Oil Processing — Session 11, 41:00
- [x] Logistics Mk. 4 — Session 13, 25:40
- [x] Fluid Packaging — Session 13, 33:25
- [x] Petroleum Power — Session 13, 42:22

---

## Primary Goals

- [x] Build Motor line — 5/min Stator, 5/min Motor (Session 10)
- [x] Locate oil node(s) — Session 12
- [x] Build oil extraction — 4 extractors, 360/min crude (Session 12)
- [x] Build refinery lines — Rubber 20/min, Plastic 20/min (Session 13)
- [ ] Overclock Unit A (Steel Pipe) — power slug in inventory, carried from Tier 4
- [x] Road network: Spine road Motor Factory → HUB (Session 12)

---

## MAM

| Unlock | Tree | Session |
|--------|------|---------|
| — | — | — |

---

## New Nodes Discovered

| Resource | Purity | Location | Notes |
|----------|--------|----------|-------|
| Iron | Pure | 3857, -1869 area | Motor Factory supply (Mk.2 miner) |
| Copper | Pure | 3799, -1696 | Motor Factory supply |
| Coal | Normal x2 | 3970, -2629 | Coal Mine 2 — Motor Factory fuel supply |
| Oil | Impure x2 | TBD | Active — piped to refinery |
| Oil | Normal x2 | TBD | Active — piped to refinery |

---

## Motor/Stator Factory (Built Session 10, Detail Recorded Session 11)

**Coal Supply — Coal Mine 2**

| Component | Detail | Location | Draw |
|-----------|--------|----------|------|
| 2x Mk.2 Miner on 2 Normal Coal nodes | Coal for fuel + trucked to Motor Factory | 3970, -2629 | 30 MW |
| Truck Stop (Coal Mine 2) | — | 3970, -2629 | 20 MW |
| Road | Coal Mine 2 → Motor Factory | — | — |
| **Subtotal** | | | **50 MW** |

**Iron Supply**

| Component | Detail | Location | Draw |
|-----------|--------|----------|------|
| 1x Mk.2 Miner on Pure Iron | Adjacent to Motor Factory truck stop | 3857, -1869 area | 15 MW |

**Copper Supply**

| Component | Detail | Location | Draw |
|-----------|--------|----------|------|
| 1x Mk.1 Miner on Pure Copper | Feeding Motor Factory | 3799, -1696 | 4 MW |

**Motor Factory Truck Stop**

| Component | Detail | Location | Draw |
|-----------|--------|----------|------|
| Truck Stop | Receives coal from Coal Mine 2 | 3857, -1869 | 20 MW |

**Production Equipment**

| Detail | Draw |
|--------|------|
| Motor Factory internal (Stator 5/min, Motor 5/min) | 218.9 MW |

**Motor/Stator Factory Total Draw**

| Category | Draw |
|----------|------|
| Coal Mine 2 (miners + truck stop) | 50 MW |
| Motor Factory truck stop (receive) | 20 MW |
| Mk.2 Iron Miner | 15 MW |
| Mk.1 Copper Miner | 4 MW |
| Production equipment | 218.9 MW |
| **Total** | **307.9 MW** |

---

## Oil Extraction (Built Session 12)

| Component | Detail | Draw |
|-----------|--------|------|
| 2x Oil Extractor (Impure) | — | — |
| 2x Oil Extractor (Normal) | — | — |
| **Total Output** | **360/min Crude Oil** | **160 MW** |
| 4x Pipeline Pump | Extractors → Refinery buffer tanks | TBD |

- Oil delivered via pipeline (road couldn't reach extractors)
- 2x Industrial Fluid Buffer at refinery site receiving crude
- Refinery site is road-connected via spine road extension
- Extractor and refinery locations to be recorded next session

---

## Rubber & Plastic Factory (Built Session 13)

| Line | Output | Power |
|------|--------|-------|
| Rubber | 20/min | — |
| Plastic | 20/min | — |
| Petroleum Coke (Heavy Oil Residue byproduct) | 90/min → AWESOME Sink | 20.5 MW |
| **Factory Total** | — | **80.5 MW** |

- Petroleum Coke refinery at 75% clock
- Production equipment: 60 MW

---

## Production at Tier Completion

| Item | Rate | Method |
|------|------|--------|
| Iron Rods | 30/min | Automated |
| Screws | 120/min | Automated |
| Iron Plates | 40/min | Automated |
| Wire | 60/min | Automated |
| Cable | 30/min | Automated |
| Reinforced Plate | 5/min | Automated |
| Copper Sheet | 30/min | Automated |
| Rotor | 4/min | Automated |
| Smart Plating | 2/min | Automated |
| Modular Frame | 4/min | Automated |
| Concrete | 20/min | Automated |
| Steel Pipe | 20/min | Automated |
| Steel Beam | 30/min | Automated |
| Encased Industrial Beam | 5.835/min | Automated |
| Versatile Framework | 5/min | Automated |
| Automated Wiring | 2.5/min | Automated |
| Stator | 5/min | Automated |
| Motor | 5/min | Automated |
| Rubber | 20/min | Automated |
| Plastic | 20/min | Automated |
| Petroleum Coke | 90/min | Automated → AWESOME Sink |

---

## Power at Tier Completion

| Source | Count | Output |
|--------|-------|--------|
| Coal Generators | 16 | 1200 MW |
| HUB Biomass Burners | 2 | 40 MW |
| External Biomass Burners | 6 | 180 MW |
| **Total Supply** | | **1420 MW** |
| **Total Draw** | | **~1356 MW + pumps TBD** |

---

## Road Network Progress

- [x] Spine road: Motor Factory → Iron Mine 1 → Steel Factory → HUB (Session 12)
- [x] Off ramps: Iron Mine 1, Steel Factory, HUB, Copper Sheet Factory (Session 12)
- [x] Spine road extended: HUB → past Reinforced Plate / Copper Sheet / Modular Frame → Refinery (Session 12)
- [x] Oil extractors → Refinery (pipeline — terrain blocked road)

---

## Alternate Recipes Found

| Recipe | Source | In Use |
|--------|--------|--------|
| Wet Concrete | Hard drive (Session 11) | — |

---

## Collectibles

| Item | Count |
|------|-------|
| Mercer Sphere | 2 |

---

## Notes & Observations

- Spire Coast north ruled out as oil source — oil found past Modular Frame factory direction
- Jetpack milestone completable from existing production + Motor line (no oil needed)
- Motor/Stator factory built Session 10, detail recorded Session 11
- Road construction started Session 11, spine road completed Session 12
- Oil extractors online Session 12, crude piped to refinery buffer tanks
- Rubber & Plastic factory built Session 13, Heavy Oil Residue converted to Petroleum Coke and sunk
- All Tier 5 milestones complete Session 13

---

## Heading Into Tier 6

**Immediate priorities:**

- Record oil extractor and refinery locations
- Record pipeline pump power
- Overclock Unit A (Steel Pipe) — power slug in inventory

**Open questions:**

—

---

*Created: 2026-03-23*
