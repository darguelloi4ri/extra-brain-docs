# UC3 — Edge User Allocation (EUA) in Telecommunications

**Objective.** Maximise UEs served while minimising active edge servers, subject to compute and coverage constraints—improving latency and energy efficiency.

## Problem framing
- Variant of variable-size vector bin packing with spatial coverage and multi-resource (CPU, memory, I/O) constraints; highly dynamic and large-scale.

## BLNN-based EUA Solver
- Energy-based stochastic dynamics explore solution landscapes; parallelism improves scalability; online adaptation to mobility and demand shifts.
- FPGA acceleration targeted for low-latency, energy-efficient edge deployment; explainability for operator trust.

## High-level architecture
- **Data ingestion & pre-processing:** UE demands, server capacities & coverage; filter infeasible assignments.  
- **BLNN solver:** Assign as many UEs as possible using the least servers under constraints.  
- **Offloading execution:** Enforce assignments and monitor SLA/QoS.

## Evaluation (examples)
- Efficient edge compute usage, #UEs served, decision latency, solver energy efficiency, optimality-gap quality, scalability and XAI clarity; plus TCO and adaptability.
