# Labels (`1`–`5`)

This dataset contains labeled time-series sensor data collected from a container-mounted endpoint.

## Label meanings

### 1 — Pick from ground (Phase 1: Reach Stacker approach/pick)
The reach stacker picks the container from the ground and begins the lift/transition.

### 2 — Pick from ground (Phase 2: Lift/hold during transfer)
The container is being lifted/held by the reach stacker as the process continues toward the trailer.

### 3 — Pick from ground (Phase 3: Place onto trailer)
The reach stacker completes the placement of the container onto the trailer.

### 4 — Trailer transport (Container moved by trailer)
The container is transported while on the trailer.

### 5 — Yard placement (Pick from trailer → place in yard)
The container is picked from the trailer and placed into the yard (by the reach stacker).

## Notes
- Labels `1`, `2`, and `3` correspond to the container handling sequence from **ground → trailer** using the reach stacker.
- Label `4` is reserved for the **movement while the container is on the trailer**.
- Label `5` is for the sequence from **trailer → yard** placement.
