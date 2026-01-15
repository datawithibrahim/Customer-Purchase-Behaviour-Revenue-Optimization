# Customer Purchase Behavior Analysis  
## Building a Business Intelligence Solution That Solves Real Business Problems

---

## Why I Built This Project

I built this project after repeatedly seeing the same issue across businesses: customer counts keep increasing, but revenue does not grow at the same pace. In some cases, revenue barely grows at all. Even more concerning, most businesses cannot clearly explain why this gap exists.

This disconnect is a serious warning sign. It usually means the business is acquiring customers who are not valuable—customers who buy once, only purchase during discounts, or consistently buy low-margin products. In these cases, acquisition costs are not being justified by revenue.

I also noticed that promotions are often run without understanding their financial impact. Sales volume during promotions is treated as success, while no one asks whether those sales were incremental or simply discounted purchases that would have happened anyway. Over time, this trains customers to avoid full-price purchases and erodes margins.

The same problem appears in loyalty programs. Companies invest heavily in loyalty tiers, assuming higher tiers lead to higher spending. But in practice, higher-tier customers often do not spend meaningfully more than lower-tier or even non-members. Rewards are given without incremental return.

Finally, I saw major strategic decisions being made based on assumptions instead of evidence—uniform budgets across regions, identical promotions for all income groups, and equal treatment of all customers regardless of value.

This project was built to address those exact problems. The goal was not to showcase tools or techniques, but to produce analysis that a CEO or CFO could actually use to identify revenue risk, margin leakage, and misallocated investment.

---

## Core Business Problems Investigated

### Revenue Concentration Risk

I first analyzed how revenue is distributed across customers. If revenue is evenly spread, customer churn is manageable. If revenue is concentrated, losing a small number of customers can cause severe financial damage.

Understanding this concentration determines how much should be invested in retention, which customers deserve premium treatment, and which customers can be allowed to churn with minimal impact.

---

### Promotion Effectiveness and Margin Erosion

Promotions often appear successful because sales increase during campaign periods. However, increased volume does not automatically mean incremental revenue. If customers were going to buy anyway, promotions simply reduce margins.

Frequent promotions also train customers to wait for discounts, reducing full-price sales over time and damaging long-term profitability.

---

### Loyalty Program ROI

Most loyalty programs measure success through engagement or participation. From a business perspective, the only meaningful question is whether higher-tier customers generate significantly more revenue.

If they do not, the loyalty program becomes a cost center rather than a growth driver.

---

### Customer Acquisition Quality

When customer count grows faster than revenue, it indicates poor acquisition quality. Either the wrong segments are being targeted or the business is acquiring customers with low lifetime value.

Understanding which segments actually generate value is essential for effective marketing investment.

---

## Revenue Concentration Findings

![Purchase Distribution](https://github.com/datawithibrahim/Customer-Purchase-Behaviour-Revenue-Optimization/blob/fdf3ed7c02dc26baff090f97d5fb5d2c119b545e/Visualizations/Purchase_Distibution.png)

Revenue is heavily right-skewed. Most customers contribute small amounts, while a small group generates a disproportionate share of revenue.

This creates operational risk. Losing a few high-value customers could result in a large revenue drop. At the same time, treating all customers equally leads to inefficient resource allocation.

### Implications

- High-value customers require proactive retention and premium support  
- Low-value customers should not receive the same investment  
- Retention strategy must be value-based, not volume-based  

### Recommended Actions

| Action | Priority |
|------|---------|
| Identify and tag high-value customers | Immediate |
| Introduce premium service for key customers | High |
| Proactive outreach for revenue-critical accounts | High |
| Reduce spend on low-value retention | Medium |
| Early churn warning system for top customers | High |

---

## Income and Spending Relationship

![Income Distribution](https://github.com/datawithibrahim/Customer-Purchase-Behaviour-Revenue-Optimization/blob/fdf3ed7c02dc26baff090f97d5fb5d2c119b545e/Visualizations/Income_Distibution.png)

Income is distributed across low, mid, and high segments. Higher-income customers spend more on average, as expected.

The issue is not spending—it is discounting. High-income customers frequently use promotions despite having low price sensitivity. This results in unnecessary margin loss.

![Income Band](https://github.com/datawithibrahim/Customer-Purchase-Behaviour-Revenue-Optimization/blob/fdf3ed7c02dc26baff090f97d5fb5d2c119b545e/Visualizations/Income_Band.png)

On large revenue bases, even small discount misuse translates into substantial annual losses.

### Key Problem

Uniform promotion strategies are financially inefficient.

### Recommendations

| Action | Expected Outcome |
|------|------------------|
| Segment promotions by income | Margin protection |
| Replace discounts with value benefits for high-income customers | Maintain satisfaction |
| Target promotions only to price-sensitive segments | Incremental revenue |
| Test removing promotions for high-income users | Validate margin leakage |

---

## Purchase Frequency vs Value

Frequent buyers are not always high-value buyers. Some customers purchase often but spend little per transaction, while others purchase infrequently but generate large revenue.

Most loyalty systems reward frequency instead of value, leading to over-investment in low-value customers and under-protection of high-value ones.

### Fix Required

Reward spending, not activity.

### Recommendations

- Base loyalty tiers on annual spend  
- Separate treatment for high-value vs high-frequency customers  
- Protect infrequent high-value customers from churn  
- Reduce incentives for frequent low-value segments  

---

## Promotion Dependency Risk

Promotions often do not increase purchase value enough to offset margin loss. In several cases, discounted customers spent no more than non-discounted customers.

Some segments have become promotion-dependent, waiting for discounts before buying. This behavior is difficult to reverse and weakens competitive position.

### Recommendations

| Action | Risk |
|------|------|
| Stop blanket promotions | High |
| Use targeted promotions only | Medium |
| Replace discounts with non-price value | Low |
| Gradually reduce promotion frequency | High |
| Test promotion-free periods by region | Medium |

---

## Loyalty Program Ineffectiveness

Higher loyalty tiers do not consistently generate higher spending. This indicates that rewards are being given without incremental return.

The root issue is tier advancement based on transactions rather than revenue.

### Recommendations

| Action | Timeline |
|------|----------|
| Redesign tiers around annual spend | 3–6 months |
| Introduce spend-based multipliers | Short-term |
| Align benefits with high-value customer needs | Medium |
| Measure success by incremental revenue | Immediate |

---

## Regional Performance Variation

Regions show large differences in revenue and promotion reliance. Applying a national strategy ignores these differences and causes margin leakage.

### Regional Strategy Framework

| Region Type | Strategy |
|------------|----------|
| High revenue, low promotions | Reduce discounts |
| High revenue, high promotions | Test value alternatives |
| Low revenue, low promotions | Investigate demand barriers |
| Low revenue, high promotions | Reassess profitability |

---

## Satisfaction vs Spending Plateau

Spending increases with satisfaction only up to a point. Beyond that threshold, further experience improvements do not generate proportional revenue gains.

### Implication

There is an optimal level of customer experience investment. Anything beyond that wastes resources.

---

## Age Group Revenue Contribution

Revenue is concentrated in specific age groups. Marketing budgets should reflect actual revenue contribution, not assumptions about future value.

---

## Key Problems Exposed

- Revenue dependency on a small customer segment  
- Margin loss from untargeted promotions  
- Loyalty program not generating incremental revenue  
- Poor customer acquisition quality  
- Promotion-driven buying behavior  
- Equal treatment of unequal customers  
- Inefficient national strategies across regions  

---

## Strategic Roadmap

### Immediate

- Tag top revenue customers  
- Pause blanket promotions  
- Audit loyalty economics  

### 1 Month

- Segmented promotions  
- Premium service for key customers  
- Spend-based loyalty tiers  

### 3 Months

- Regional strategy customization  
- Refined acquisition targeting  
- Value-based segmentation rollout  

### 6 Months

- Churn prediction for high-value customers  
- Dynamic pricing  
- Executive-level performance monitoring  

---

## Expected Outcomes

| Metric | Impact |
|------|--------|
| Revenue | +8–12% |
| Margin | +3–5 pts |
| High-value retention | +15–20% |
| Promotion cost | −30–40% |
| CAC | −20–30% |
| Revenue per customer | +12–15% |

---

## Business Impact Measurement

Success will be measured through:

- Revenue growth matching customer growth  
- Margin improvement  
- High-value customer retention  
- Reduced promotion dependency  
- Higher full-price sales  
- Improved acquisition ROI  
- Narrower regional performance gaps  

The real impact is not a metric—it is the shift from assumption-driven decisions to evidence-based strategy. That is what creates sustainable advantage.
