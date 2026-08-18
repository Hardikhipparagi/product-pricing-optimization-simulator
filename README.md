# Product Pricing Optimization Simulator

## Project Overview

The **Product Pricing Optimization Simulator** is a non-coding Product Management and Business Analytics project designed to help a Product Manager evaluate different pricing strategies and identify a suitable price point.

The simulator analyzes the relationship between **price, demand, revenue, profitability, customer willingness to pay, competitor pricing, price sensitivity, churn, CAC, LTV, and unit economics**.

The project is designed to be portfolio-ready for GitHub, LinkedIn, resumes, and Product Management interviews.

## Business Problem

Companies often struggle to determine whether a product is underpriced or overpriced.

A lower price can increase customer acquisition and demand but reduce margins. A higher price can increase revenue per customer and profitability but may reduce conversion and increase churn.

This simulator allows different pricing scenarios to be tested before making an actual pricing decision.

## Objective

The objective is to build a practical pricing simulation system that helps decision-makers:

* Compare pricing strategies
* Estimate demand at different price points
* Analyze revenue and profit
* Evaluate customer willingness to pay
* Compare competitor pricing
* Analyze price elasticity
* Evaluate customer segments
* Compare pricing scenarios
* Identify a profit-maximizing tested price
* Support pricing decisions using unit economics

## Product

### SkillSprint Pro

**Category:** EdTech SaaS

**Target Customers:** Students and Individual Professionals

**Business Model:** Subscription-based digital product

**Current Price:** ₹999

SkillSprint Pro is positioned as a structured learning platform providing courses, assessments, projects, and progress analytics.

## Dataset

The project contains:

* 15-product base dataset
* 100 customer-level pricing records
* Price simulation dataset
* Scenario analysis dataset

Key variables include:

* Customer ID
* Customer Segment
* Region
* Current Price
* Proposed Price
* Competitor Price
* Unit Cost
* Willingness to Pay
* Expected Demand
* Number of Customers
* Conversion Rate
* Churn Rate
* Discount
* Revenue
* Gross Profit
* Gross Margin
* CAC
* LTV
* LTV:CAC Ratio
* Price Sensitivity
* Pricing Scenario
* Recommended Price
* Final Decision

## Pricing Methodology

The simulator evaluates several pricing approaches.

### Cost-Plus Pricing

Price is calculated using unit cost plus a markup.

### Competitor-Based Pricing

The proposed price is evaluated against competitor pricing.

### Value-Based Pricing

The price is influenced by customer willingness to pay and perceived value.

### Recommended Approach

For SkillSprint Pro, a combination of **value-based and competitor-based pricing** is used as the starting framework, followed by simulation and experimentation.

## Customer Segmentation

The analysis considers:

* Students
* Individual Professionals
* Small Businesses
* Mid-Market
* Enterprise

Each segment can differ in:

* Willingness to Pay
* Price Sensitivity
* Conversion
* Churn
* LTV
* Profitability

This supports the possibility of segment-specific pricing and packaging.

## Competitor Analysis

Competitor pricing is used as a market reference point.

The simulator does not treat competitor price as the only pricing decision factor. Customer value, willingness to pay, demand, cost structure, profitability, and retention must also be considered.

## Willingness to Pay

Customer willingness to pay can be analyzed using:

* Customer surveys
* Interviews
* Historical purchases
* A/B pricing tests
* Van Westendorp Price Sensitivity Meter
* Basic Conjoint Analysis

The objective is to identify pricing ranges perceived as:

* Too Cheap
* Acceptable
* Expensive
* Too Expensive

## Price Elasticity

Price Elasticity of Demand measures how strongly demand changes when price changes.

The simulator evaluates these tested prices:

|  Price |
| -----: |
|   ₹499 |
|   ₹699 |
|   ₹899 |
|   ₹999 |
| ₹1,199 |
| ₹1,499 |
| ₹1,999 |

For each price point, the model evaluates:

* Expected Demand
* Conversion Rate
* Expected Customers
* Revenue
* Cost
* Profit
* Gross Margin
* Churn

## Pricing Simulator

The Excel simulator allows pricing assumptions to be evaluated through a structured model.

### Key Inputs

* Proposed Price
* Expected Demand
* Conversion Rate
* Unit Cost
* CAC
* Churn
* Discount
* Price Elasticity

### Key Outputs

* Customers
* Revenue
* Gross Profit
* Gross Margin
* LTV
* LTV:CAC
* Revenue Growth
* Profit Growth

## Scenario Analysis

Five scenarios are included:

1. **Penetration Pricing**
2. **Current Pricing**
3. **Moderate Increase**
4. **Premium Pricing**
5. **Promotional Discount**

The scenarios compare:

* Price
* Customers
* Revenue
* Profit
* Margin
* Churn

## Key Results

Based on the tested model scenarios:

| Objective          | Tested Price |
| ------------------ | -----------: |
| Maximum Customers  |         ₹499 |
| Maximum Revenue    |         ₹699 |
| **Maximum Profit** |     **₹899** |

The current modeled price is **₹999**.

The initial model therefore identifies **₹899 as the profit-maximizing tested price**.

This is a simulation result and should be validated using real customer and experiment data before a production pricing change.

## Dashboard

The Excel dashboard contains:

* Current Price KPI
* Recommended Price KPI
* Maximum Revenue KPI
* Maximum Profit KPI
* Gross Margin KPI
* LTV:CAC KPI
* Price vs Profit visualization
* Scenario Revenue comparison
* Product Manager Recommendation section

The project brief also identifies additional dashboard views such as:

* Price vs Demand
* Price vs Revenue
* Price vs Conversion
* Competitor Pricing
* Willingness to Pay
* Customer Segment Profitability
* Price Sensitivity
* Scenario Comparison
* Subscription Plan Comparison

## Business Insights

The simulator demonstrates several important pricing principles:

1. The price that maximizes customers may not maximize revenue.
2. The price that maximizes revenue may not maximize profit.
3. Higher prices can improve margin when variable costs remain stable.
4. Demand can decline as price increases.
5. Churn should be monitored during price increases.
6. Competitor pricing is an important market reference.
7. Customer willingness to pay should constrain premium pricing.
8. Segment-specific pricing may improve product-market fit.
9. Discounts can increase adoption while reducing margin.
10. LTV:CAC connects pricing decisions with acquisition economics.

## Product Manager Recommendation

### Current Price

**₹999**

### Initial Recommended Test Price

**₹899**

The model identifies ₹899 as the profit-maximizing tested price among the simulated price points.

However, the recommendation should not be rolled out immediately.

The Product Manager should first run a controlled pricing experiment and evaluate:

* Conversion
* Revenue per Visitor
* Churn
* ARPU
* LTV
* Profit
* Customer Segment performance

## Pricing Experiment

### Control Group

Current Price: **₹999**

### Test Group

Proposed Price: **₹899**

### Metrics

* Conversion Rate
* Revenue per Visitor
* Churn
* ARPU
* LTV
* Profit

The new price should be launched more broadly only if the test demonstrates stronger overall economics without unacceptable retention or customer-value risks.

## Tools Used

### Mandatory

* Microsoft Excel
* GitHub

### Optional

* Power BI
* Tableau
* SQL
* Python
* AI tools

## Repository Structure

```text
product-pricing-optimization-simulator/
│
├── data/
│   ├── Base_Data.csv
│   ├── Customer_Pricing_Data.csv
│   ├── Price_Simulation.csv
│   └── Scenario_Analysis.csv
│
├── analysis/
│
├── dashboard/
│   └── Product_Pricing_Optimization_Simulator.xlsx
│
├── pricing-simulator/
│   └── Product_Pricing_Optimization_Simulator.xlsx
│
├── screenshots/
│   └── pricing-optimization-dashboard.png
│
├── docs/
│   └── Product_Pricing_Optimization_Strategy_Report.docx
│
└── README.md
```

## Project Files

### `/data`

Contains the datasets used for pricing analysis and simulation.

### `/analysis`

Contains supporting analysis and future analytical outputs.

### `/dashboard`

Contains the dashboard version of the Excel simulator.

### `/pricing-simulator`

Contains the main pricing simulation workbook.

### `/screenshots`

Contains dashboard screenshots for portfolio presentation.

### `/docs`

Contains the strategy report and supporting documentation.

## Future Scope

Future versions can integrate:

* Actual transaction data
* Product usage data
* Customer cohort analysis
* Real A/B pricing experiment results
* Churn prediction
* Advanced demand forecasting
* Segment-specific pricing
* Usage-based pricing
* Automated Power BI dashboards
* SQL-based analytics pipelines

## Interview Summary

I built a non-coding Product Pricing Optimization Simulator to help a Product Manager choose a price by balancing demand, revenue, profitability, and retention.

I modeled multiple price points using price elasticity, competitor pricing, willingness to pay, and unit economics. I then compared revenue, profit, margin, customers, and churn across different pricing scenarios.

The model identified ₹899 as the profit-maximizing tested price versus the current modeled price of ₹999. I would validate that recommendation through a controlled A/B pricing experiment before a full rollout.

## Portfolio

This project demonstrates practical skills in:

* Product Management
* Pricing Strategy
* Revenue Optimization
* Price Elasticity
* Customer Segmentation
* Willingness to Pay
* Unit Economics
* CAC
* LTV
* Product Analytics
* Scenario Analysis
* Business Strategy
* Excel Modeling
* Dashboard Development
* Data-Driven Decision Making
