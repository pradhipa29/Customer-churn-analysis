# Customer Churn Analysis
### Telecom Customer Retention Intelligence | Python · Jupyter

## Overview

A telecom company is silently losing 1 in 4 customers every month.
This project digs into 7,032 customer records to find exactly why —
and puts a dollar figure on the damage.

Using Python for deep exploratory analysis and Power BI for
interactive reporting, this project surfaces the contract types,
payment behaviors, and customer profiles driving the highest churn.

## Business Problem

> *"Which customers are leaving, why are they leaving,
> and how much revenue is walking out the door?"*

## Key Findings

| Metric | Value | Insight |
|--------|-------|---------|
| Overall Churn Rate | 26.6% | 1 in 4 customers leaving |
| Month-to-Month Churn | 42.7% | 14x higher than two-year contracts |
| Two-Year Contract Churn | 2.8% | Most loyal segment |
| Avg Monthly Charge — Churned | $74.44 | $13 more than retained customers |
| Avg Monthly Charge — Retained | $61.31 | Healthy customer baseline |
| Total Revenue Lost | $2,862,926 | Majority from short-term contracts |
| Avg Tenure — Churned | 18 months | New customers are highest risk |
| E-check Churn Rate | 45% | 2x higher than auto-pay customers |

## Business Recommendations

**1. Convert month-to-month customers to annual contracts**
Churn drops from 43% to 3% — the single highest-impact action.

**2. Prioritize new customer onboarding (0–12 months)**
Churn is highest in the first year. Early engagement programs
can significantly reduce early exits.

**3. Migrate customers to auto-pay**
Electronic check users churn at 2x the rate of auto-pay customers.
Incentivize switching with discounts or loyalty points.

**4. Review pricing for high-charge customers**
Churned customers pay $13/month more on average.
A targeted retention offer for high-charge segments could
recover a significant portion of the $2.86M revenue loss.


## Project Structure
```
customer-churn-analysis/
│
├── churn_analysis.ipynb      # Full Python EDA notebook
├── churn_summary.csv         # Key findings summary table
├── churn_rate.png            # Overall churn pie chart
├── churn_contract.png        # Churn by contract type
├── churn_tenure.png          # Churn by tenure
├── churn_charges.png         # Monthly charges distribution
├── churn_internet.png        # Churn by internet service
├── churn_heatmap.png         # Correlation heatmap

## Tools & Technologies

| Tool | Usage |
|------|-------|
| Python 3.x | Core analysis language |
| Pandas | Data cleaning & manipulation |
| Matplotlib & Seaborn | Data visualization |
| Jupyter Notebook | Analysis environment |
| Power BI | Interactive dashboard |

## Dataset

- **Source:** IBM Telco Customer Churn
- **Platform:** Kaggle
- **Size:** 7,032 customers · 21 features
- **Link:** [View Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## How to Run
# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch notebook
jupyter notebook churn_analysis.ipynb

## Author

**Pradhipa S** — Data Analyst
