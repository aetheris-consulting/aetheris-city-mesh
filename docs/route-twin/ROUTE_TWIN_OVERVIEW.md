# RouteTwin Overview

## Definition

RouteTwin is the movement and mission execution twin for City Mesh.

It simulates and verifies movement across:

- robot patrol routes
- drone paths
- inspection vehicles
- public works crews
- emergency response routing
- maintenance missions
- ecological survey paths

## RouteTwin Flow

```text
mission objective
→ route candidate
→ constraints
→ simulation
→ risk classification
→ approval
→ execution
→ telemetry
→ after-action update
```

## Route Risk Classes

```yaml
route_risk:
  R0: observation path only
  R1: low-risk patrol
  R2: reversible operational route
  R3: consequential public route / disruption
  R4: emergency / life-safety route
```

Routes that affect public safety, traffic, emergency services, or physical actuators require Gate 8 approval.
