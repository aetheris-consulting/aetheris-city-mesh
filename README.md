# Aetheris City Mesh

**Aetheris City Mesh** is a governed smart-area, civic, and ecological intelligence architecture.

It connects the Aetheris control stack — **AHA, WEOF, AHA-SIM, D2L, Nexus, NeuroMedic, THOS, Gate 8, WFKB/WFKC** — to a city/ecosystem-scale deployment layer for urban, rural, coastal, desert, forest, ocean, and atmospheric domains.

## Core Thesis

City Mesh senses the world.  
THOS describes what was sensed.  
D2L classifies evidence quality.  
Nexus maps causal relationships.  
NeuroMedic diagnoses system pathology.  
AHA-SIM tests interventions.  
WEOF governs response.  
Gate 8 commits or blocks action.  
WFKB/WFKC preserves the learning.

## Safety Doctrine

- Novelty is not authority.
- Simulation is not truth.
- Proposal is not action.
- Candidate state is not committed state.
- Intelligence must pass through structure before it touches authority.
- City Mesh may sense broadly and simulate deeply, but it may only act through governed authority.

## CAD/SIM/MAP Extension

This repo includes a first-pass **CAD/SIM/MAP** layer for City Mesh.

```text
city object
→ map layer
→ CAD/geometry object
→ simulation scene
→ route/movement twin
→ Gate 8 commit packet
```

New profiles and objects:

- `THOS-CAD` — geometry, design, FreeCAD-style model metadata
- `THOS-MAP` — GIS/map layers, tiles, features, geofences
- `RouteTwin` — route, patrol, mission, and movement simulation
- `SceneTwin` — lightweight digital twin scene manifest
- `CADCommitPacket` — governed CAD/design change proposal
- `MapCommitPacket` — governed map/state change proposal

The key rule remains:

**Map/CAD/simulation updates are candidate state until Gate 8 commits them.**

## Near-Term MVP

```text
robot/sensor anomaly
→ THOS telemetry packet
→ D2L evidence classification
→ Nexus causal map
→ NeuroMedic diagnosis
→ AHA-SIM city-twin test
→ WEOF workflow route
→ Gate 8 commit/reject
→ audit + WFKB update
```

Start with a low-risk civic workflow:

- pothole detection
- blocked storm drain
- streetlight outage
- tree stress anomaly
- air-quality anomaly
- debris / hazard report
