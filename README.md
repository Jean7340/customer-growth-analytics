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
| Marketing Incrementality | Did marketing campaigns generate incremental sales? | Geo Experiments, Incrementality Analysis, Difference-in-Differences | [View Report](output/01_marketing_incrementality.html) |
| Customer Response Prediction | Which customers are most likely to respond? | Classification, Feature Engineering, Model Evaluation | HTML Report |
| Facebook Advertising Performance Analysis | Which advertising strategies perform best? | Exploratory Data Analysis, Marketing Analytics, KPI Analysis | HTML Report |

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

### Marketing Incrementality Analysis

A retailer wanted to know whether its regional advertising campaign actually drove incremental revenue. Using data from a geo-based experiment, I compared treatment and control markets with Difference-in-Differences analysis to separate campaign impact from underlying market trends. The results indicated no statistically significant incremental lift, providing evidence against scaling the campaign in its current form.

<p align="center">
  <img src="figures/Revenue Trends by Market.png" width="700">
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

---

## Key Takeaways

Across these projects, the focus is not only on building analytical models, but also on translating analytical findings into business decisions.

The analyses emphasize:

- Defining business problems
- Selecting appropriate analytical methods
- Interpreting results
- Communicating actionable recommendations
