# End-to-End-Pricing-Intelligence-and-Revenue-Optimization-System

## Table of Contents

[Project Overview](#project-overview)

[Summary of Findings](#summary-of-findings)

[Analysis of Findings](#analysis-of-findings)

---
## Project Overview

**Stakeholder:** Chief Revenue Officer (CRO)

**Purpose:** This project is an evaluation of whether revenue growth is  sustainable or overly dependent on discount escalation

**About the dataset:**

**Dataset Overview:** The dataset is built to support pricing, revenue, and growth analysis, with a strong focus on understanding how discount strategies, competition, and customer behavior influence demand and revenue outcomes. 

**Business Context:** Indian e-commerce operates in a highly price-sensitive and promotion-driven environment, where aggressive discounting, intense competition, and regional demand variation play a critical role in business performance. This dataset mirrors that reality by capturing how pricing decisions, discount levels, competition intensity, inventory pressure, and sales events interact to shape customer demand and revenue across different product categories and Indian states.

**Time Structure:** The dataset spans 36 months of activity. The emphasis is on monthly trends and strategic decision-making, not granular daily behavior.

**Dataset Structure & Variables:** The dataset contains transaction-level records with variables covering:
- Order identification and reporting date
- Geographic information (state and zone)
- Product category and brand type (Mass / Premium)
- Pricing variables (base price, discount percentage, final price)
- Demand and outcome metrics (units sold, revenue)
- Market context indicators (sales events, competition intensity, inventory pressure)
- Basic customer demographics (age and gender)

*Each variable is included to support pricing sensitivity, revenue analysis, and growth-related decision-making.*

**Key Assumptions Embedded in the Data:**
1. Discounts increase demand only up to an optimal threshold.
2. Excessive discounting leads to diminishing revenue returns.
3. Premium brands maintain stronger pricing discipline.
4. Festival periods drive volume spikes but not always higher profitability.
5. Price sensitivity varies significantly across Indian states and customer segments.
6. Competition intensity and inventory pressure influence discounting behavior

*These assumptions are embedded in the data patterns, not imposed during analysis.*

**Project Question:** Is revenue growth sustainable, or is it increasingly dependent on reactive discount escalation influenced by competition, inventory pressure, and event-driven volume spikes?

**Focus:**
- Revenue growth quality
- Discount-led vs. organic growth
- Strategic risk
- Discount optimisation (pricing)

**Stack:**
- Excel/Google Sheets
- SQL
- Power BI

**Excel is for:**
- Initial exploration
- Business-style ad hoc analysis
- Pricing simulations
- What-if modelling

## Summary of Findings:

### Excel:

#### 1. Customer Demographics
- Young Adults contributed 48.1% of total revenue.
- Youth contributed 30.6%.
- Elderly contributed 4.8%.
- Revenue contribution aligns with discount utilization — younger groups received and used a higher proportion of discounts.
- Revenue split by gender is approximately 50–50, indicating no material gender-based variation.

#### 2. Brand Type Performance
**Mass brands account for:**
- 78% of total units sold
- 75% of total discounts
- Average discount: 42%

**Premium brands:**
- Lower volume contribution
- Average discount: 27%

**Revenue contribution:**
- Mass ranges between 4%–36%
- Premium ranges between 1%–13%
- Discount levels vary by brand type and age group.
- Premium brands maintain lower discount levels across all customer segments.

#### 3. Sales Events
**Festival events:**
- 25% of total orders
- 35% of total revenue
- 38% of total units sold
- Higher average revenue per order and higher units per order

**Normal sales:**
- 65% of total revenue

*Festival periods produce higher transaction intensity.*

#### 4. Growth Trends
- Monthly revenue and unit growth fluctuated between +15% and below -10%.
- Growth frequently diverged between revenue and unit metrics.
- 3-month rolling averages hover around zero.
- No sustained upward growth trend observed across the 36-month period.

#### 5. Competition & Inventory Pressure
- 45% of total orders originate from medium competition environments.
- High competition environments show greater volatility.
- High inventory pressure periods correlate with higher discount levels and elevated volatility.

**High competition + High inventory pressure:**
- 48% average discount
- 7% of total revenue

**Medium competition + Low inventory pressure:**
- 31% of total revenue
- 36% average discount

#### 6. Discount Behavior & Elasticity
- Orders increase within the 21–30% discount range.
- Orders peak within the 31–40% range.
- Orders decline beyond 41%.
- Revenue contribution peaks between 21–40%.
- Discounts above 50% increase units sold but reduce revenue efficiency.
- Revenue-based discount impact shows higher volatility than unit-based impact.

## Analysis of Findings
### Excel:
#### 1. Revenue Concentration Risk

Revenue is concentrated among younger, discount-responsive segments. This introduces:
- Customer demographic dependency
- Sensitivity to promotional intensity
- Limited diversification across age cohorts

*Gender was not found to be a differentiator and therefore is not a pricing lever.*

#### 2. Business Model Positioning

The data suggests:
- Mass brands drive scale through high discounting.
- Premium brands maintain pricing discipline but contribute less volume.

The current structure appears volume-driven rather than margin-optimized. Premium strategy exists but does not dominate revenue contribution.

#### 3. Growth Quality Assessment

Growth behavior indicates:

- Oscillation rather than compounding expansion.
- Periods where unit growth exceeds revenue growth suggest discount-led expansion.
- Periods where revenue growth exceeds unit growth suggest healthier pricing conditions.

However, sustained structural growth is not evident across rolling averages. Growth appears event- and promotion-driven.

#### 4. Discount Optimisation Insight

The 21–40% discount band represents the most revenue-efficient range.

Discounting beyond 50% produces:
- Increased volume
- Reduced revenue efficiency
- Higher volatility

This suggests non-linear elasticity and diminishing returns at higher discount levels. Current discounting may not always be calibrated to maximize revenue efficiency.

#### 5. Competitive & Operational Pressure Effects

Medium competition environments produce the most stable growth.

**High competition environments:**
- Increase volatility
- Correlate with deeper discounting

**High inventory pressure:**
- Triggers aggressive pricing
- Leads to short-term spikes
- Followed by revenue correction

This indicates reactive rather than strategic pricing behavior during operational stress.
