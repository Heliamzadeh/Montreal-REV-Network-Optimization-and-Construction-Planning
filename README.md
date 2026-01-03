# Montreal-REV-Network-Optimization-and-Construction-Planning
Urban Network Optimization · Operations Research · Decision Analytics · Infrastructure Planning


## Overview
This project develops a **data-driven optimization and planning framework** for the expansion of Montreal’s *Réseau Express Vélo (REV)* network. The work integrates **network analysis, cost–demand trade-off modeling, constrained scheduling, and sensitivity analysis** to support long-horizon infrastructure investment decisions under limited resources.

The objective is not only to select high-impact cycling corridors, but to **optimize construction sequencing and team allocation** while respecting budget, capacity, and temporal constraints.

---

## Problem Formulation
Urban cycling infrastructure expansion involves competing objectives:

- Maximize mobility demand coverage
- Minimize capital expenditure
- Respect construction capacity and workforce limits
- Ensure feasible long-term schedules under seasonal productivity constraints

This project formulates the REV expansion as a **network-level planning and scheduling problem**, where candidate corridors compete for limited construction resources over a multi-year horizon.

---

## Data & Network Representation
Each corridor is modeled as a **network segment** with associated attributes:

- Length (km)
- Construction cost ($M)
- Estimated demand (BIXI trips)
- Cost efficiency (cost per km)
- Temporal and resource requirements

Corridors are evaluated both independently and collectively to assess **system-level impact** rather than isolated performance.

---

## Methodology

### 1. Corridor Selection & Trade-off Analysis
- Comparative analysis of corridor length, cost, and demand
- Cost-efficiency metrics to prioritize high-impact investments
- Demand-weighted evaluation of network expansion benefits

### 2. Network-Level Planning
- Selection of non-overlapping corridors to maximize coverage
- Aggregation of total network length, cost, and demand served
- Spatial visualization of selected corridors over the Montreal network

### 3. Construction Scheduling & Resource Allocation
- Multi-year construction timeline (quarterly resolution)
- Team-to-corridor assignment under capacity constraints
- Makespan minimization subject to:
  - Maximum available teams
  - Corridor-specific construction rates
  - Sequential and parallel execution constraints

### 4. Sensitivity & Scenario Analysis
Systematic evaluation of planning robustness under:
- Varying planning horizons (6–10 years)
- Different construction productivity rates
- Seasonal productivity effects (winter vs summer)
- Changes in workforce availability

These analyses quantify how operational assumptions affect feasibility, duration, and resource utilization.

---

## Key Results
- Identification of an **optimal subset of corridors** maximizing demand coverage within budget
- Feasible construction schedules with **bounded workforce requirements**
- Clear trade-offs between project duration, team availability, and construction rates
- Demonstrated robustness of the selected plan across multiple scenarios

---

## Visualization Outputs
The project includes:
- Corridor-level cost, demand, and efficiency comparisons
- Spatial network maps of selected REV corridors
- Gantt-style construction timelines
- Team assignment schedules
- Sensitivity curves linking resources to project duration

These visualizations function as **decision-support tools**, not just exploratory plots.

---

## Technical Stack
- Python
- Pandas, NumPy
- Matplotlib
- Network modeling & scheduling logic
- Scenario simulation and sensitivity analysis

---

## Applications
This framework generalizes to:
- Urban infrastructure planning
- Transportation network expansion
- Capital project portfolio optimization
- Public-sector decision analytics

---

## Notes
This project emphasizes **modeling, optimization logic, and decision reasoning** rather than black-box prediction, reflecting real-world constraints faced by municipalities and infrastructure planners.

