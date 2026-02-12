# Analysis Guide

This document provides a structured overview of the analytical workflow used in this project. It is intended to help non-technical readers, reviewers, and business stakeholders understand the purpose of the analysis without requiring detailed inspection of the underlying code.

---

## Analytical Scope

The analysis focuses on evaluating historical QRIS transaction behavior and assessing suitable forecasting approaches for two distinct outcome variables:
- Transaction volume
- Nominal transaction value

The primary objective is to support business and policy-oriented decision-making through interpretable and context-aware forecasting results.

---

## Role of the SARIMAX Model

The SARIMAX model is implemented as a baseline multivariate time series approach to evaluate the statistical relevance of selected exogenous variables. Its primary role is diagnostic rather than purely predictive, enabling assessment of whether external drivers meaningfully contribute to transaction dynamics.

The results from this model inform methodological decisions and guide the selection of final forecasting strategies.

---

## Analytical Workflow Overview

1. Data preparation and transformation to ensure time series consistency.
2. Exploratory analysis to identify trend and seasonal characteristics.
3. SARIMAX model estimation to test exogenous variable significance.
4. Interpretation of model outputs with emphasis on business relevance rather than statistical metrics alone.

---

## Interpretation Guidance

Readers are encouraged to focus on:
- Direction and stability of estimated effects
- Differences between volume and nominal value dynamics
- Implications for strategic planning and ecosystem monitoring

Technical implementation details are secondary to analytical reasoning and insight generation.
