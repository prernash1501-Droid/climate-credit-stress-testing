# Climate Credit Stress Testing

Climate transition risk stress testing of an SME loan portfolio in Python: NGFS scenarios (GCAM) linked to stressed PD, LGD and Expected Loss, with an automated scenario pipeline.

> Work in progress. This README will be completed as each step is built.

## Objective
Estimate how credit losses on a small-business loan portfolio change under different climate transition pathways, and identify the sectors most sensitive to transition risk.

## Data
- **Climate scenarios:** NGFS Scenario Explorer (GCAM model, USA region): carbon price, GDP, sector emissions
- **Loan portfolio:** US SBA small-business loan data (public)

## Method (planned)
1. Baseline PD (logistic regression scorecard), LGD and EAD
2. Map borrower industries (NAICS) to transition-risk sensitivity
3. Translate scenario carbon-price and GDP paths into stressed PD and LGD
4. Compare Expected Loss across scenarios, years and sectors
5. Sensitivity analysis on key stress assumptions
6. Automated, config-driven scenario pipeline and report

## Project structure
```
config/      scenario settings
data/        raw and processed data (not committed)
notebooks/   step-by-step analysis
src/         reusable pipeline code
reports/     results and figures
```

## Progress
- [ ] Step 1 – Concepts
- [ ] Step 2 – Data
- [ ] Step 3 – Baseline PD / LGD / EAD
- [ ] Step 4 – Sector mapping
- [ ] Step 5 – Scenario stressing
- [ ] Step 6 – Results and sensitivity
- [ ] Step 7 – Automation
- [ ] Step 8 – Final write-up
