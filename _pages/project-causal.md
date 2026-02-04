---
title: "Causal Inference in Healthcare"
permalink: /project-causal/
---

### One-line summary  
Estimated treatment effects from observational healthcare data using causal inference frameworks, with emphasis on assumptions and robustness.

---

### Problem  
In many healthcare settings, randomized experiments are infeasible or unethical. This project focused on estimating causal treatment effects from observational data while carefully addressing confounding and identification assumptions.

### Data  
- Observational healthcare dataset  
- Patient-level covariates, treatment indicators, and outcomes  
- Moderate sample size typical of applied health studies

### Approach  
- Formal causal framework using potential outcomes  
- Propensity score modeling (matching / weighting)  
- Regression adjustment for remaining imbalance  
- DAG-based reasoning to clarify identification assumptions

### Validation  
- Covariate balance checks after adjustment  
- Sensitivity analysis to assess robustness  
- Comparison across multiple estimation strategies

### Results  
- Estimated average treatment effects under stated assumptions  
- Demonstrated sensitivity to model specification and overlap  
- Highlighted the importance of transparency in causal claims

### Assumptions & Limitations  
- No unmeasured confounding  
- Correct specification of propensity score model  
- Limited external validity beyond the observed population

### What I would do next  
- Apply doubly robust or machine-learning–based estimators  
- Explore heterogenous treatment effects  
- Extend framework to policy or economic decision contexts

### Artifacts  
- Code repository  
- Methodology report  
- Slides summarizing causal assumptions

