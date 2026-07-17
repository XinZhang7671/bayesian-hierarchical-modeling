# Bayesian Hierarchical Modeling
This repository contains a Bayesian hierarchical logistic regression project developed for the Bayesian Methods course at Lund University.
The project models contraceptive use among Bangladeshi women using fixed-effects and multilevel Bayesian models implemented in Stan. Multiple model specifications were compared using posterior diagnostics and WAIC to identify the best-performing model.
<p align="center">
  <img src="dag2.png" width="650">
</p>

**Variables**
- **C**: Contraceptive use (0 = No, 1 = Yes)
- **D**: District of residence
- **L**: Number of living children
- **A**: Standardized centered age
- **U**: Urban residence (0 = Rural, 1 = Urban)

**Figure 1.** Final Bayesian hierarchical logistic regression model with district-level effects and an interaction between age and living children.
## Workflow
1. Load Bangladesh Fertility Survey
2. Build Bayesian Logistic Regression
3. Develop Hierarchical Model
4. Compare Models using WAIC
5. Posterior Prediction
6. Counterfactual Analysis
## Project Overview
This project investigates contraceptive use among Bangladeshi women using Bayesian logistic regression models. Three model specifications were developed and compared:

- Fixed-effects logistic regression
- Bayesian hierarchical logistic regression
- Bayesian hierarchical model with an interaction between age and living children

Model performance was assessed using posterior diagnostics and the Widely Applicable Information Criterion (WAIC). The final model was further evaluated through posterior predictive checks and counterfactual analysis.
