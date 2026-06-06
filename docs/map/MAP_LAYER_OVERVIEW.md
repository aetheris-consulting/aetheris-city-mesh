# City Mesh Map Layer

## Purpose

The map layer gives City Mesh a geospatial memory and operating picture.

It stores:

- points
- lines
- polygons
- routes
- geofences
- sensor zones
- robot patrol cells
- anomaly locations
- asset references
- ecological observation zones
- digital twin boundaries

## Map Layer Types

```yaml
map_layers:
  - base_city
  - infrastructure
  - roads_routes
  - utilities
  - environmental
  - biological
  - atmospheric
  - public_safety
  - robot_patrol
  - anomalies
  - candidate_interventions
  - committed_repairs
```

## Candidate vs Committed Map State

```text
candidate_map_feature:
  proposed, observed, unverified, or simulated

committed_map_feature:
  approved, authoritative, auditable city state
```

Gate 8 decides whether candidate map changes become committed city state.
