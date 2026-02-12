# Executive Results Summary

## Project Objective
This project aims to support strategic and analytical decision-making by examining historical patterns and forecasting future dynamics of QRIS (Quick Response Code Indonesian Standard) transaction activity in Indonesia. The analysis focuses on understanding growth behavior, seasonality, and the role of exogenous factors in shaping transaction volume and nominal value over time.

Rather than prioritizing model complexity alone, the analytical objective emphasizes interpretability and business relevance, ensuring that the results can inform policy discussions, operational planning, and digital payment ecosystem development.

---

## Key Analytical Findings

### 1. Transaction Volume Dynamics
Transaction volume exhibits a strong and persistent upward trend, reflecting sustained growth in QRIS adoption and usage. The deterministic trend model captures this long-term structural growth effectively, indicating that volume expansion is driven primarily by systematic adoption rather than short-term fluctuations.

Seasonal patterns are present but relatively stable, suggesting predictable cyclical behavior that can be incorporated into forward planning without requiring overly complex stochastic structures.

---

### 2. Nominal Transaction Value Behavior
In contrast, nominal transaction value demonstrates higher volatility and sensitivity to external factors. SARIMAX modeling reveals that exogenous variables contribute meaningfully to explaining nominal value movements, supporting the use of multivariate time series approaches for financial magnitude forecasting.

This distinction highlights that while usage intensity grows structurally, transaction value is more responsive to economic conditions, merchant behavior, and payment ecosystem expansion.

---

### 3. Role of SARIMAX as a Baseline Model
SARIMAX is employed primarily as a baseline analytical tool to evaluate the relevance and statistical contribution of exogenous variables. The results confirm that external drivers play a significant role in nominal value dynamics, validating their inclusion from a business and policy perspective.

Final forecasting decisions prioritize model stability and interpretability, aligning methodological choices with practical analytical objectives rather than purely statistical performance.

---

## Business and Strategic Implications
The findings support differentiated analytical strategies for volume and value forecasting. Deterministic trend models provide reliable long-term projections for transaction volume, while multivariate approaches are more appropriate for nominal value planning and scenario analysis.

From a business analytics standpoint, these results enable stakeholders to anticipate infrastructure demand, evaluate adoption trajectories, and assess the potential impact of ecosystem-level interventions on transaction behavior.

---

## Intended Audience
This summary is designed for business analysts, policymakers, and decision-makers who require clear, evidence-based insights without deep technical exposure to time series modeling methodologies.
