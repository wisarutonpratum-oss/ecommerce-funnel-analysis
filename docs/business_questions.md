# Business Questions — E-Commerce Funnel Analysis

## Project Objective
This dashboard was designed to analyze the e-commerce purchase funnel and identify where users drop off before completing a purchase. It also evaluates whether conversion performance differs across customer segments, acquisition channels, and campaign types in order to support optimization decisions.

The analysis focuses on the journey from **website visit → product view → add to cart → checkout → purchase**, and aims to answer both **conversion efficiency** and **revenue performance** questions.

---

# 1) Core Business Questions

This project was built to answer the following stakeholder questions:

### Funnel Performance
- How many users progress through each stage of the e-commerce funnel?
- Where is the largest drop-off in the customer journey?
- What is the overall session-to-purchase conversion rate?

### Customer & Channel Conversion
- Do conversion rates differ by **device**, **channel**, or **user type**?
- Is mobile traffic underperforming compared with desktop?
- Are returning users more likely to convert than new users?
- Which acquisition channels bring the highest conversion efficiency?

### Campaign & Revenue Performance
- Which campaign types generate the highest revenue?
- Are campaign differences driven by conversion efficiency or by traffic volume?
- Which region contributes the most revenue?
- How do sessions, purchases, and revenue trend over time?

### Decision-Making Questions
- Should the business prioritize funnel optimization, device optimization, or marketing channel investment?
- Is the business losing more value from weak conversion efficiency or from poor progression through a specific funnel stage?
- What additional data would be required to evaluate marketing effectiveness more accurately?

---

# 2) Dashboard Pages and Business Questions

## Page 1 — Executive Overview

### Purpose
This page provides a high-level summary of funnel performance and answers the question:

> **“How effectively does the business convert website sessions into purchases, and where does the biggest drop-off happen in the funnel?”**

### Visuals Included
- **KPI Cards**
  - Total Sessions
  - Total Purchases
  - Total Revenue
  - Overall Conversion Rate
  - Average Order Value (AOV)

- **Funnel Chart**
  - Website Visit → Product View → Add to Cart → Checkout → Purchase

- **Donut Chart**
  - Sessions by Purchase Completion

### Business Questions Answered
- How much traffic does the business generate overall?
- How many sessions convert into purchases?
- What is the total revenue generated from all completed purchases?
- What is the average revenue per completed order?
- Which stage of the funnel experiences the greatest user drop-off?
- What share of sessions end in a completed purchase vs. no purchase?

### Why This Page Matters
This page establishes the overall performance baseline of the e-commerce funnel. It helps stakeholders quickly understand whether the business problem is primarily:
- a **traffic problem**,
- a **conversion problem**, or
- a **funnel drop-off problem**.

It also acts as the entry point for the rest of the dashboard by identifying where deeper investigation is needed.

---

## Page 2 — Conversion Analysis

### Purpose
This page compares conversion performance across major customer and acquisition segments. It answers the question:

> **“Are some customer groups or traffic sources converting more efficiently than others?”**

### Visuals Included
- **Conversion Rate by Device** — Bar Chart
- **Conversion Rate by Channel** — Bar Chart
- **Conversion Rate by User Type** — Bar Chart

### Business Questions Answered

#### Device Analysis
- Do **mobile** and **desktop** users convert at different rates?
- Should the business prioritize device-specific UX optimization?

#### Channel Analysis
- Which traffic channels drive the highest conversion rate?
- Are **Paid Ads**, **Organic**, **Social**, and **Email** equally efficient in converting sessions into purchases?
- Is a high-revenue channel actually high-performing, or is it simply generating more traffic volume?

#### User Type Analysis
- Are **returning users** more likely to convert than **new users**?
- Is user familiarity with the brand associated with stronger purchase behavior?

### Why This Page Matters
This page helps separate **volume-driven performance** from **conversion-driven performance**.

For example:
- A channel may generate high revenue simply because it brings a large number of sessions, not because it converts efficiently.
- A device may appear important due to traffic share, but if conversion rates are similar across devices, it may not be the right optimization priority.

This page therefore supports more focused decisions about **channel optimization**, **audience strategy**, and **experience improvement priorities**.

---

## Page 3 — Campaign & Revenue Analysis

### Purpose
This page extends the funnel analysis into **business impact** by examining which campaigns, regions, and months contribute most to revenue. It answers the question:

> **“Which campaigns and business segments generate the strongest revenue outcomes, and are those outcomes driven by traffic volume or conversion efficiency?”**

### Visuals Included
- **Revenue by Campaign Type** — Clustered Bar Chart
- **Conversion Rate by Campaign Type** — Clustered Column Chart
- **Revenue by Region** — Clustered Bar Chart
- **Monthly Revenue & Purchases Trend** — Line and Clustered Column Chart

### Business Questions Answered

#### Campaign Type Analysis
- Which campaign type generates the highest revenue?
- Which campaign type converts best?
- Are differences between campaigns driven by **conversion rate** or by **session volume**?
- Should the business scale one campaign type more aggressively than others?

#### Regional Revenue Analysis
- Which region contributes more revenue to the business?
- Is the business more dependent on **Metro** or **Non-Metro** demand?

#### Time Trend Analysis
- How stable are purchases and revenue across months?
- Are there signs of growth, decline, or seasonality in business performance?
- Is revenue moving in line with purchase volume, or are there changes in order value over time?

### Why This Page Matters
Page 3 connects funnel performance to **commercial outcomes**. While the first two pages focus on conversion and customer behavior, this page helps answer broader business questions about where revenue is coming from and how sustainable performance appears over time.

This page is particularly useful for decision-making around:
- **campaign prioritization**
- **budget allocation**
- **market focus**
- **monitoring monthly business health**

---

# 3) How the Dashboard Supports Business Decisions

Taken together, the three dashboard pages guide the business through a structured decision flow:

## Step 1 — Identify the Funnel Bottleneck
**Page 1** reveals whether the largest problem occurs at the awareness stage, product engagement stage, cart stage, or checkout stage.

Example decision:
- If the biggest drop-off is between **Product View** and **Add to Cart**, the business should investigate product-page effectiveness, pricing communication, product trust signals, and call-to-action design.

## Step 2 — Test Whether the Problem Is Segment-Specific
**Page 2** checks whether underperformance is concentrated in a specific device, traffic source, or customer group.

Example decision:
- If mobile conversion is much lower than desktop, the business should prioritize mobile UX improvements.
- If channel conversion differs significantly, the marketing team should review channel quality and landing-page alignment.

## Step 3 — Evaluate Revenue Impact and Prioritization
**Page 3** helps determine which campaigns and business segments matter most commercially.

Example decision:
- If one campaign type drives the highest revenue but has only average conversion, its value may come from scale rather than efficiency.
- If monthly revenue is stable but purchases are declining, the business may need to investigate changes in average order value or promotional strategy.

---

# 4) Recommended Actions Based on This Dashboard

This dashboard is designed to support decisions such as:

- improving the weakest funnel stage rather than optimizing the entire journey at once
- validating whether channel investment decisions should be based on conversion performance or traffic contribution
- identifying whether mobile/desktop optimization should be prioritized
- comparing new vs. returning user conversion behavior
- monitoring whether campaign performance translates into actual revenue impact
- assessing whether more data is needed before making marketing budget decisions

---

# 5) Important Limitations of the Analysis

While this dashboard is effective for funnel and conversion analysis, it does not provide a complete view of marketing efficiency or long-term customer value.

### Current limitations include:
- **No marketing cost data**, so metrics such as **ROAS**, **CAC**, or campaign profitability cannot be calculated.
- **No detailed customer transaction history**, so **Customer Lifetime Value (CLV)** and retention behavior cannot be analyzed.
- Funnel outcomes are measured at the **session level**, which means repeat user behavior across multiple sessions is not fully captured.

These limitations are important when interpreting channel and campaign performance. A high-revenue channel is not necessarily the most cost-effective one, and a strong first-purchase funnel does not automatically imply strong long-term customer value.

---

# 6) Summary

This dashboard was built to answer one central business question:

> **How can the business improve e-commerce conversion performance by identifying funnel drop-offs, understanding segment-level conversion behavior, and linking campaign activity to revenue outcomes?**

By combining funnel monitoring, segment comparison, and campaign revenue analysis, the dashboard provides a practical framework for prioritizing conversion optimization and supporting better marketing decisions.
