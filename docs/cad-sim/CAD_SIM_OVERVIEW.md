# CAD/SIM Extension Overview

## Purpose

The CAD/SIM extension lets City Mesh represent physical objects, infrastructure, routes, facilities, and repair proposals as simulation-addressable objects.

It connects:

```text
physical asset
→ map feature
→ CAD object
→ simulation scene
→ workflow intervention
→ Gate 8 commit
```

## Why CAD matters

City Mesh cannot only sense city state. It also needs structured geometry for:

- roads
- bridges
- storm drains
- buildings
- utilities
- parks
- robot patrol routes
- hazard zones
- repair objects
- temporary infrastructure
- proposed interventions

## Canonical Flow

```text
Sensor detects condition
→ THOS telemetry packet created
→ map feature updated as candidate state
→ CAD object linked or generated
→ simulation scene tests intervention
→ WEOF routes workflow
→ Gate 8 commits, rejects, quarantines, or escalates
```

## Candidate-State Doctrine

A generated CAD model, repair object, map edit, or simulation result is not authoritative.

```text
CAD proposal != built environment
simulation result != truth
map candidate != civic record
```
