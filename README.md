📘 IFRS 9 – ECL Modelling (Python + Excel)

This project demonstrates an end-to-end IFRS 9 Expected Credit Loss (ECL) framework covering:

📌 1. Data Preparation
Input dataset (loan-level)
Risk attributes & behaviour variables
Curing, defaults & write-offs

📌 2. Staging Logic

Stage 1, Stage 2, Stage 3 rules
SICR indicators
DPD-based movements

📌 3. PD Estimation

12-month Point-in-Time PD
Lifetime PD curve construction
Survival analysis & transition logic

📌 4. LGD Estimation

Retail rule-based LGD
Recovery rate assumptions
Write-off behaviour

📌 5. EAD Calculation

Exposure at Default rules
Credit conversion factors

📌 6. ECL Calculation

Stage-wise ECL
Multiplying PD × LGD × EAD × discount factor
Portfolio-level ECL summary

📌 7. Monitoring & Governance

Back-testing
Model drift checks (PSI/CSI)
ECL reconciliation
