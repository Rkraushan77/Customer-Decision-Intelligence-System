# Customer Decision Intelligence System

An end-to-end customer analytics and decision intelligence project designed to identify high-value customers at risk, quantify revenue exposure, and generate actionable retention, win-back, re-engagement, and cross-sell strategies.

The project combines **Python/Pandas-based customer analytics** with an interactive **Power BI decision dashboard** to transform raw transactional data into business-focused customer actions.

---

## 📌 Project Overview

Customer retention is critical for businesses because losing high-value customers can directly impact revenue.

Traditional customer analysis often focuses on descriptive metrics such as total sales or number of customers. This project goes further by answering business questions such as:

- Which customers are most valuable and currently at risk?
- How much historical revenue is associated with these customers?
- Which customers require immediate intervention?
- What retention or win-back action should be taken?
- Which product categories are most relevant for at-risk customers?
- Where are potential cross-sell opportunities?
- How can potential revenue recovery be estimated under different scenarios?

The final solution converts customer behavior into a **prioritized customer action queue** and presents the results through a **3-page Power BI dashboard**.

---

## 🎯 Business Objectives

1. Identify high-value customers showing signs of inactivity.
2. Quantify historical revenue exposure from at-risk customers.
3. Develop customer-level priority scores.
4. Segment customers based on risk and business value.
5. Generate actionable retention and re-engagement strategies.
6. Identify category-level product opportunities.
7. Estimate potential revenue recovery using scenarios.
8. Build an executive-friendly Power BI dashboard for decision-making.

---

## 📊 Dataset

The project uses four interconnected datasets.

| Dataset | Records | Description |
|---|---:|---|
| Customers | 50,000 | Customer demographics and acquisition information |
| Orders | 220,000 | Customer order history |
| Order Items | 424,819 | Product-level transaction details |
| Products | 1,000 | Product, category, brand and pricing information |

### Key Customer Fields

- Customer ID
- Signup Date
- Gender
- Age
- City
- State
- Acquisition Channel
- Customer Type
- Income Band

### Key Transaction Fields

- Order ID
- Customer ID
- Product ID
- Quantity
- Selling Price
- Cost Price
- Discount

---

# 🔄 Project Workflow

```text
Raw Business Data
       │
       ▼
Data Understanding
       │
       ▼
Data Preparation
       │
       ▼
Exploratory Data Analysis
       │
       ▼
Customer-Level Analysis
       │
       ▼
Customer Risk & Value Scoring
       │
       ▼
Critical Customer Identification
       │
       ▼
Product & Category Analysis
       │
       ▼
Action & Recommendation Logic
       │
       ▼
Revenue Recovery Scenarios
       │
       ▼
Executive KPI Dataset
       │
       ▼
Power BI Dashboard
