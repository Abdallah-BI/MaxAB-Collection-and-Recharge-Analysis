# ABMAX Collection Operations & Recharge Cost Analysis

## Project Overview

This project analyzes collection operations performance, delay and recovery behavior, and recharge method costs to identify operational risks, operational improvement opportunities, and cost optimization strategies.

The analysis combines SQL, Power BI, DAX, and business intelligence techniques to transform operational data into actionable business insights and recommendations.

---

## Business Objectives

* Evaluate collection operations performance.
* Monitor agent productivity and completion efficiency.
* Analyze delay and recovery lifecycle behavior.
* Identify root causes behind performance fluctuations.
* Evaluate recharge method costs and efficiency.
* Discover opportunities to reduce operational costs.
* Provide actionable recommendations to improve business performance.

---

## Tools & Technologies

* SQL
* Power BI
* DAX
* Data Modeling
* Business Intelligence
* Data Analysis

---

## Dashboard 1: Operations Performance

### Key KPIs

* Total Orders
* Success Rate
* Failed Rate
* Delay Rate
* Completion Time
* Average Handle Time (AHT)
* Productivity
* Reassignment Rate
* Data Quality Metrics

### Analysis Areas

* Weekly Success Rate Trend
* Agent Completion Performance
* Zone Performance Overview
* Operational Efficiency by Zone

### Key Insight

Collection operations maintained a consistently high success rate throughout the analysis period, with overall success exceeding 98%, demonstrating strong operational performance and effective agent execution.

---

## Dashboard 2: Delay & Recovery Analysis

### Key KPIs

* Delay Rate
* Recovery Rate
* Delayed Orders
* Final Success Rate
* Final Failed Rate
* Final Delayed Rate

### Analysis Areas

* Direct Delay Analysis
* Recovery Funnel
* Delay Outcome Breakdown
* Zone Delay Distribution
* Weekly Delay Trend

### Key Findings

* Only a small percentage of orders experienced delays.
* Most delayed orders were successfully recovered.
* Recovery operations played a significant role in maintaining final collection success rates.
* Delayed orders that were not recovered represented the primary source of collection failures.

### Root Cause Analysis

Week 15 recorded the lowest success rate during the analysis period.

Investigation showed that the decline was not caused by agent capacity or operational workload, as productivity and completion time remained relatively stable.

The primary driver was an increase in delayed orders that subsequently converted into failed collections.

### Recommendation

Implement proactive monitoring for delayed orders and establish escalation rules for zones experiencing delayed-to-failed transitions.

Early intervention could prevent delays from turning into final failures and protect overall success rates.

---

## Dashboard 3: Recharge Method Cost Analysis

### Key KPIs

* Total Transactions
* Recharge Value
* Processing Cost
* Digital Usage %
* Collection %
* Cost Ratio
* Cost per Transaction

### Analysis Areas

* Cost by Channel
* Cost Trend Over Time
* Transaction Value vs Cost
* Payment Method Cost Trend
* Recharge Method Distribution

### Key Findings

Digital Wallet became the dominant recharge channel while maintaining competitive processing costs.

The App channel demonstrated lower processing costs compared to POS, indicating more efficient recharge behavior.

A significant cost-saving opportunity exists through recharge method optimization.

### Break-Even Analysis

The break-even point between Digital Wallet and Collection is approximately 2,869 EGP.

* Below 2,869 EGP → Digital Wallet is more cost-efficient.
* Above 2,869 EGP → Collection is more cost-efficient.

### Recommendation

Implement a value-based recharge routing strategy for POS transactions.

Route transactions below the break-even threshold through Digital Wallets and transactions above the threshold through Collection whenever operationally feasible.

### Business Impact

Recharge processing costs could potentially be reduced from approximately 3M EGP to 1.5M EGP, representing nearly 50% cost savings.

---

## Executive Insights & Recommendations

### Insight #1 – Performance Risk

#### Finding

Week 15 recorded the lowest success rate during the analysis period.

#### Root Cause

Investigation showed that the decline was not caused by agent capacity or operational workload, as productivity and completion time remained relatively stable.

The primary driver was an increase in delayed orders that subsequently converted into failed collections.

#### Recommendation

Implement proactive monitoring for delayed orders and establish escalation rules for zones experiencing delayed-to-failed transitions.

---

### Insight #2 – Recovery Excellence

#### Finding

Several zones achieved 100% recovery rates.

#### Key Finding

Top-performing zones achieved 100% recovery rates, demonstrating effective delay management and consistent operational execution.

#### Recommendation

Review the operational practices of zones that achieved 100% recovery rates and replicate them across zones with lower recovery performance.

---

### Insight #3 – Cost Optimization Opportunity

#### Finding

A significant cost-saving opportunity exists through recharge method optimization.

#### Key Finding

The break-even point between Digital Wallet and Collection is approximately 2,869 EGP.

* Below 2,869 EGP → Digital Wallet is more cost-efficient.
* Above 2,869 EGP → Collection is more cost-efficient.

#### Recommendation

Implement a value-based recharge routing strategy for POS transactions.

Route transactions below the break-even threshold through Digital Wallets and transactions above the threshold through Collection whenever operationally feasible.

#### Business Impact

Potential recharge processing costs could be reduced from approximately 3M EGP to 1.5M EGP, representing nearly 50% cost savings.

---

### Insight #4 – Channel Efficiency

#### Finding

The App channel operates at a lower processing cost than POS.

#### Key Finding

Although the App channel relies exclusively on Digital Wallet recharges, its overall processing cost remains lower than POS, indicating a more cost-efficient recharge channel.

#### Recommendation

Increase App adoption through retailer awareness campaigns, incentives, and digital engagement initiatives to shift more transactions toward the lower-cost channel.

---

## Overall Business Impact

* Maintain a 98.88% final success rate through stronger delay management.
* Improve recovery performance by replicating best practices from top-performing zones.
* Reduce recharge processing costs by up to 1.5M EGP through optimized recharge method selection.
* Increase App adoption to further improve cost efficiency and operational scalability.

---

## Skills Demonstrated

* SQL Query Development
* Data Cleaning & Validation
* Data Modeling
* DAX Measures
* KPI Design
* Dashboard Development
* Root Cause Analysis
* Business Intelligence
* Data Storytelling
* Business Recommendations

---

## Author

Abdallah Mahmoud

Data Analyst Portfolio Project
