# Customer Growth Analytics

> Business analytics case studies focused on customer behavior, marketing effectiveness, campaign optimization, and data-driven growth decisions.

This repository contains end-to-end customer and growth analytics case studies focused on marketing effectiveness, customer behavior, and campaign optimization.

The projects demonstrate how analytics supports business decisions from problem definition to actionable recommendations.

---

## Business Questions

This repository explores questions such as:

- Which marketing activities generate incremental business value?
- Which customers are most likely to respond?
- Which advertising strategies improve campaign performance?
- How can marketing resources be allocated more effectively?

---

## Projects

| Project | Business Question | Methods | Deliverables |
|----------|-------------------|---------|-------|
| Advertising Performance Analysis | Which advertising strategies drive better campaign performance? | Exploratory Data Analysis, Performance Analysis, Multiple Linear Regression | [View Report](output/01_facebook_advertising_performance_analysis.html) |
| Marketing Incrementality | Did marketing campaigns generate incremental sales? | Geo Experiments, Difference-in-Differences, Causal Inference | [View Report](output/02_marketing_incrementality.html) |
| Customer Response Prediction | Which customers are most likely to respond? | Classification, Predictive Modeling, Campaign Targeting | [View Report](output/03_customer_response_prediction.html) |

---

## Analytics Workflow

Every project follows a consistent analytics workflow:

1. Define the business problem
2. Explore and prepare the data
3. Build analytical models
4. Evaluate results
5. Generate business recommendations

---

## Featured Projects

### Advertising Performance Analysis

This project evaluates how placement, ad format, retail category, creative messaging, and audience characteristics influence advertising performance. Using exploratory data analysis, ANOVA, and regression analysis, I found that advertising efficiency varies across campaign attributes, with placement and creative characteristics remaining important predictors after controlling for other factors. The findings were translated into recommendations for campaign optimization.

<p align="center">
  <img src="figures/campaign_attributes_click_efficiency.png"
       alt="Campaign Attributes Click Efficiency"
       width="900">
</p>

### Marketing Incrementality Analysis

A retailer wanted to know whether its regional advertising campaign actually drove incremental revenue. Using data from a geo-based experiment, I compared treatment and control markets with Difference-in-Differences analysis to separate campaign impact from underlying market trends. The results indicated no statistically significant incremental lift, providing evidence against scaling the campaign in its current form.

<p align="center">
  <img src="figures/revenue_trends_by_market.png"
       alt="Revenue Trends by Market"
       width="900">
</p>

https://jean7340.github.io/customer-growth-analytics/02_marketing_incrementality.html

### Customer Response Prediction

A bank wanted to improve the efficiency of its telemarketing campaigns by identifying customers who were most likely to subscribe to a term deposit. Using historical campaign data, I developed a predictive targeting model that ranked customers by their likelihood of responding and translated model predictions into a practical targeting strategy. By prioritizing high-propensity customers instead of contacting everyone, the analysis demonstrated how predictive analytics can improve campaign efficiency and marketing resource allocation.

<p align="center">
  <img src="figures/campaign_targeting_simulation.png"
       alt="Campaign Targeting Simulation"
       width="900">
</p>

---

## Tools & Technologies

- Python
- R
- Quarto
- Jupyter Notebook
- Scikit-learn
- pandas
- ggplot2

---

## Repository Structure

```text
customer-growth-analytics/
│
├── README.md
├── 01_marketing_incrementality/
├── 02_customer_response_prediction/
├── 03_facebook_advertising_performance_analysis/
└── images/
```
