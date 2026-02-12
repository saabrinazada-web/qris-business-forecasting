# QRIS Transaction Forecasting: A Business-Oriented Analytical Study

## 1. Background and Context
Quick Response Code Indonesian Standard (QRIS) has become a core component of Indonesia’s digital payment infrastructure, reflecting both transaction behavior and the pace of cashless payment adoption. Understanding historical transaction patterns and producing reliable forecasts are essential for supporting strategic planning, monitoring growth dynamics, and informing policy and business-related decision-making.

Time series forecasting, when applied appropriately, enables analysts to identify underlying trends, seasonal structures, and forward-looking patterns that are relevant beyond short-term fluctuations. However, model selection must be aligned with data characteristics and analytical objectives rather than driven solely by methodological complexity.

## 2. Analytical Objectives
This project aims to conduct a structured analysis of QRIS transaction data with the following objectives:
- To examine trend and seasonal behavior in QRIS transaction volume and nominal value.
- To evaluate the relevance of exogenous variables in explaining transaction dynamics.
- To develop forecasting approaches that prioritize interpretability, stability, and business relevance.
- To translate analytical results into insights that can support strategic and decision-oriented perspectives.

## 3. Data Overview
The analysis utilizes monthly QRIS transaction data over a multi-year period, consisting of:
- Transaction volume
- Transaction nominal value
- Exogenous variables related to merchant growth and digital payment adoption

In addition to time series data, survey-based validation was employed to contextualize forecasting results from a behavioral perspective, supporting interpretative alignment rather than methodological triangulation.

## 4. Modeling Strategy and Rationale
Given the distinct characteristics of the target variables, separate modeling strategies were applied to transaction volume and transaction nominal value.

### 4.1 Transaction Volume
For transaction volume, a deterministic trend regression model was selected as the final forecasting approach. This decision was based on the model’s ability to provide a stable representation of long-term movement while maintaining interpretability for strategic analysis.

A SARIMAX model was implemented as a baseline analytical tool to examine the statistical relevance of exogenous variables. The purpose of this step was not to establish SARIMAX as the final forecasting model for transaction volume, but to assess whether external factors contribute meaningful explanatory information beyond trend-based dynamics.

### 4.2 Transaction Nominal Value
For transaction nominal value, a SARIMAX model incorporating exogenous variables was employed as the final forecasting model. The nominal transaction series exhibits dynamic behavior that benefits from incorporating external influences, making SARIMAX an appropriate choice for capturing both autoregressive patterns and exogenous effects.

This differentiated modeling strategy reflects an analytical emphasis on model suitability rather than uniform methodological application.

## 5. Evaluation and Interpretation
Model evaluation was conducted using appropriate accuracy metrics and diagnostic assessments to ensure reliability and consistency. Beyond numerical performance, particular attention was given to interpretability and the alignment between model outputs and analytical objectives.

Forecasting results were interpreted in relation to observed trends, seasonal behavior, and potential implications for strategic planning and monitoring of QRIS transaction activity.

## 6. Key Insights and Implications
The analysis indicates sustained growth and recurring seasonal patterns in QRIS transactions. Forecasting outcomes provide forward-looking perspectives that may support:
- Monitoring transaction growth dynamics
- Anticipating seasonal fluctuations
- Informing planning and evaluation related to digital payment systems

These insights are intended to support analytical understanding and decision-oriented interpretation rather than precise prediction of future values.

## 7. Repository Structure
The repository is organized to reflect a logical analytical workflow, guiding readers from data understanding through modeling and result interpretation. Folder naming and numbering are designed to support clarity and accessibility for both technical and non-technical audiences.

## 8. Notes and Scope
This project is derived from an academic study and has been reframed to emphasize its relevance for business analysis and strategic insight. While methodological rigor is maintained, the primary focus remains on analytical reasoning and interpretative value rather than exhaustive methodological comparison.
