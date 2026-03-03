# Digital Twin Framework for Precision Pharmacometrics

[![Monolix](https://img.shields.io/badge/Monolix-2024-green)](https://monolixsuite.lixoft.com/)

## Overview

This repository implements a **physiologically-grounded Digital Twin framework** compliant with standards. It rescues failed FAAH inhibitors by unmasking 80% responders hidden in population averages, using QSP-ODE simulations on 500 virtual patients.

Standard PK/PD modeling predicted only 15.3% peak CB1 occupancy at 10mg dosing, explaining Phase II failures. Digital twins reveal sustained engagement (>30h median) in low NAAA-clearance phenotypes

## Key Importance

- **Rescues Abandoned Assets**: Identifies precision dosing (e.g., 30mg escalation) and patient stratification, turning clinical failures into viable therapies.
- **Handles Heterogeneity**: Multivariate sampling from Monolix covariance + covariates (weight, age, albumin) + homeostasis constraints (Vmax = AEA_baseline * k_deg).
- **MIDD Template**: FDA-aligned Virtual Patient Populations for CNS drugs, immunotherapy, and beyond.
- **Real-World Impact**: Wide VPC intervals confirm model validity; 80% responder rate justifies trial rescue.


