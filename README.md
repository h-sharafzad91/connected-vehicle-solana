# Blockchain-Based Trust Management for Connected Vehicle Networks

**Academic research project | MSc Data Science & AI**

This project investigates a blockchain-supported trust-management approach for connected-vehicle networks. It combines traffic simulation, behavioural trust evaluation, and Solana-based recording of trust-related data to explore how decentralised infrastructure could support accountability in a dynamic vehicular environment.

## Research objectives

- Simulate connected-vehicle behaviour in a SUMO traffic environment.
- Evaluate vehicle behaviour and derive trust scores.
- Explore malicious-behaviour detection using the collected simulation data.
- Integrate Solana smart contracts to record selected trust information.
- Study system behaviour through monitoring and performance measurements.

## System components

| Component | Role |
|---|---|
| SUMO / TraCI | Vehicle and traffic simulation |
| Python backend | Simulation control, behavioural analysis, and trust processing |
| Solana / Anchor | On-chain program integration |
| React frontend | Visual monitoring and interaction |
| Data analysis | Evaluation of detection and system-performance results |

## Research workflow

```text
SUMO vehicle simulation
        │
        ▼
Behaviour observations
        │
        ▼
Trust evaluation and detection
        │
        ▼
Solana program integration
        │
        ▼
Monitoring and experimental analysis
```

## Technology

- **Simulation:** SUMO, TraCI
- **Backend and analysis:** Python, Flask, NumPy, Pandas, scikit-learn
- **Blockchain:** Solana, Anchor, AnchorPy, solders
- **Frontend:** React
- **Visualisation:** Matplotlib and related scientific Python tooling

## Repository structure

```text
backend/                 Simulation integration and processing
frontend/                Monitoring interface
sumo/                    Traffic-network and route configuration
solana-smart-contract/   Solana program
monitoring_results/      Experimental outputs and visualisations
```

## Experimental context

The work was evaluated in a simulated environment rather than a live vehicular deployment. Reported experimental observations from the dissertation include a 6,000-second simulation involving 96 vehicles, 651 trust updates, a malicious-detection precision of 1.00, recall of 0.55, F1-score of 0.71, and median trust-update latency of 5.58 seconds.

These figures describe that experiment only; they should not be interpreted as production-network performance or generalised guarantees.

## Setup

The project requires Python, SUMO, Node.js, and the Solana / Anchor toolchain. Python dependencies are listed in `requirements.txt`. SUMO and the Solana toolchain must be installed separately.

Start with the simulation configuration and backend scripts in the repository. Blockchain deployment commands should only be run against a development cluster unless a separate deployment plan is in place.

## Scope

This repository represents an academic prototype and experimental research artefact. It is not a production connected-vehicle security system.

## Author

Research and implementation by [Hossein Sharafzad](https://github.com/h-sharafzad91).
