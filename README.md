# QRIS Transaction Forecasting: A Business-Oriented Analytical Study

**Academic Thesis Title (English Version):**  
Forecasting QRIS Transaction Volume and Nominal Value in Indonesia Using Deterministic Trend and SARIMAX Models with Exogenous Variables and Cashless Behavior Survey Validation

---

## 1. Background and Business Context

Quick Response Code Indonesian Standard (QRIS) has become a key component of Indonesia’s digital payment ecosystem, reflecting structural changes in transaction behavior and accelerating cashless adoption. As QRIS usage expands across consumer segments and merchant categories, understanding historical transaction dynamics and anticipating future trends becomes increasingly important for strategic planning, policy evaluation, and business decision-making.

From a business analytics perspective, transaction volume and nominal transaction value capture different dimensions of ecosystem growth. Transaction volume primarily reflects adoption intensity and usage frequency, while nominal transaction value is more sensitive to economic conditions, merchant behavior, and payment infrastructure development. Distinguishing these dynamics is essential to produce forecasts that are not only statistically sound but also decision-relevant.

---

## 2. Analytical Objective

This project aims to support data-driven decision-making by analyzing historical QRIS transaction patterns and producing interpretable forecasts for both transaction volume and nominal transaction value. The analysis prioritizes methodological clarity, interpretability, and business relevance rather than model complexity alone.

Specifically, the study evaluates appropriate modeling strategies for different transaction dimensions and assesses the role of exogenous variables in explaining transaction dynamics.

---

## 3. Data Sources and Analytical Scope

This study utilizes both secondary and primary data to ensure analytical robustness and contextual validation.

### 3.1 Secondary Data
Secondary data were obtained from Bank Indonesia (BI) and consist of monthly time series observations spanning approximately 65 periods. The dataset includes QRIS transaction volume and nominal transaction value, along with exogenous indicators such as the number of QRIS merchants and MSME merchant growth. These variables capture structural adoption patterns and ecosystem-level dynamics within Indonesia’s digital payment system.

### 3.2 Primary Data
Primary data were collected through a nationwide survey involving approximately 400 Indonesian university students. The survey focuses on cashless payment behavior and adoption tendencies. Rather than serving as direct model inputs, the survey data function as a validation instrument to contextualize and interpret the forecasting results from a behavioral perspective.

---

## 4. Methodological Framework

Two complementary modeling approaches are employed to reflect the distinct characteristics of the outcome variables:

- **Transaction Volume:** Modeled using a deterministic trend approach to capture long-term structural growth driven by adoption dynamics.
- **Nominal Transaction Value:** Modeled using SARIMAX with exogenous variables to evaluate the contribution of external drivers and assess multivariate time series behavior.

SARIMAX is positioned as a baseline analytical tool to test the statistical relevance of exogenous variables and inform methodological decisions, rather than being treated as the sole or final forecasting solution.

---

## 5. Key Insights and Business Relevance

The analysis indicates that transaction volume exhibits a strong and persistent upward trend, suggesting that QRIS growth is primarily driven by systematic adoption rather than short-term volatility. In contrast, nominal transaction value demonstrates greater sensitivity to external factors, supporting the use of multivariate approaches for financial magnitude forecasting.

From a business analytics standpoint, these findings support differentiated forecasting strategies: deterministic trend models are suitable for long-term volume planning, while SARIMAX-based approaches are more appropriate for evaluating policy scenarios, merchant expansion strategies, and ecosystem-level interventions affecting transaction value.

---

## 6. Project Structure
- **README.md**: Business-oriented project overview and analytical framing  
- **results_summary.md**: Executive-level summary of key findings and implications  
- **analysis/**: Technical evidence, including the baseline SARIMAX notebook and analysis guide  

---

## Intended Audience

This repository is designed for business analysts, policymakers, and decision-makers seeking clear, evidence-based insights into QRIS transaction dynamics, without requiring deep technical engagement with time series modeling code.
