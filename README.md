# Telecom-Customer-Churn-Why-Customers-Leave-and-Which-Customers-Are-Most-at-Risk
# Telecom Customer Churn Analysis

**Tools:** PostgreSQL | Power BI
**Project Type:** Telecom Analytics | Customer Retention
**Focus:** Customer Churn | Customer Behavior | Retention Risk

[View Detailed Report on GitHub]
[Back to Portfolio]

---

## Project Overview

Customer churn is a major concern for telecom businesses because losing customers affects recurring revenue and makes it harder to maintain a stable customer base.

In this project, I used **PostgreSQL and Power BI** to analyze telecom customer data and understand where churn is concentrated, why customers reported leaving, when customers are most likely to churn, and how churned customers differ from those who stayed.

Rather than looking at churn as one overall percentage, I broke the problem down into customer reasons, contract and internet segments, tenure, payment methods, and service adoption to identify the areas that deserve the most attention.

---

## Goal

<div class="highlight-box">

<p>
To understand the main patterns behind customer churn, identify the customer groups with higher churn rates, and provide retention actions based on the areas where churn is most concentrated.
</p>

</div>

---

## Business Questions

The analysis focused on five main questions:

### 1. How serious is the churn problem?

* How many customers have churned?
* What percentage of customers have churned?
* What does the churned customer population represent in terms of customer revenue?

### 2. Why are customers leaving?

* Which churn categories account for the largest share of churn?
* What reasons are customers reporting for leaving?

### 3. Which customer segments have the highest churn?

* How does churn vary by contract type?
* Does internet type show differences in churn?
* Which contract and internet combinations require closer attention?

### 4. When are customers most likely to churn?

* How does churn change as customer tenure increases?
* Which tenure groups have the highest churn rates?

### 5. What separates customers who leave from those who stay?

* How do stayed and churned customers differ by contract type?
* How does churn vary by payment method?
* Is service adoption different between customers who stayed and those who churned?

---

## Key Findings

### Competitor-Related Reasons Account for the Largest Share of Churn

**Competitor** was the largest churn category, accounting for approximately **45% of churned customers**.

Customers commonly reported that competitors offered better devices, better offers, more data, or higher download speeds.

This suggests that the business should pay close attention to how its offer compares with competing providers and whether customers clearly understand the value they are receiving.

---

### Month-to-Month Customers Have the Highest Churn

Churn was highest among **month-to-month customers**, while customers on longer-term contracts recorded substantially lower churn rates.

The difference suggests that customers without a longer-term commitment represent an important group for retention efforts.

Where appropriate, the business could test longer-term plan offers while making sure customers understand the value of the plans rather than simply pushing customers into longer contracts.

---

### Newer Customers Are More Likely to Churn

Churn rate was highest among customers with shorter tenure and generally decreased as tenure increased.

This makes the early part of the customer relationship an important period for retention.

The business could strengthen onboarding and early customer engagement, particularly by making sure customers understand the benefits of the services they have subscribed to.

---

### Churn Differs Across Payment Methods

The analysis showed differences in the proportion of stayed and churned customers across payment methods.

**Mailed Check** customers showed a higher churn proportion, while **Credit Card** customers showed a higher stayed proportion.

This does not mean payment method itself causes churn, but it identifies customer groups that may be worth monitoring more closely.

---

### Customers Without Selected Services Show Higher Churn Proportions

Customers without selected services such as **Online Security, Online Backup, and Premium Tech Support** generally showed higher churn proportions than customers who subscribed to those services.

This suggests an opportunity to make the benefits of these services clearer during onboarding and throughout the customer relationship.

---

## Dashboard

The Power BI dashboard brings the main findings together through:

* Total Customers
* Churned Customers
* Churn Rate
* Total Customer Revenue
* Customer Churn by Category
* Churn by Contract and Internet Type
* Churn by Tenure
* Stayed vs Churned Customers by Payment Method

### The dashboard was designed to answer one question quickly:

<div class="highlight-box">

<p>
<strong>Where is customer churn concentrated, why are customers leaving, and which customer groups should the business pay closer attention to?</strong>
</p>

</div>

---

## Process

* I prepared and explored the telecom customer dataset.
* I used PostgreSQL to calculate churn metrics and investigate customer churn patterns.
* I compared churn across contract types, internet types, tenure groups, payment methods, and selected services.
* I examined the recorded reasons and categories reported by churned customers.
* I used the analysis to identify the findings that were most important for the dashboard.
* I built an interactive Power BI dashboard to present the main retention insights clearly.

---

## Technical Approach

### PostgreSQL

The SQL analysis used:

* Aggregate Functions
* CASE Statements
* Filtering
* GROUP BY
* Window Functions
* PARTITION BY
* Conditional Calculations
* Churn Rate Calculations
* Segment Analysis

The SQL work was used to move from the overall churn figure into more specific questions about **why customers leave, where churn is concentrated, and how customer characteristics differ between stayed and churned customers.**

### Power BI

The dashboard includes:

* KPI Cards
* Churn Category Analysis
* Contract & Internet Type Analysis
* Tenure Analysis
* Payment Method Comparison
* DAX Measures
* Interactive Filtering
* Business-Focused Data Storytelling

---

## Recommendations

Based on the analysis, I recommend:

* Benchmark competing offers to understand what customers perceive as better and where the current offer may be falling behind.
* Give greater retention attention to **month-to-month customers**, particularly where other risk indicators are present.
* Strengthen the onboarding experience for newer customers and clearly communicate the benefits of key services.
* Monitor customer groups with higher churn proportions by payment method.
* Make the value of services such as Online Security, Online Backup, and Premium Tech Support clearer to customers.
* Track churn across these segments regularly to see whether retention efforts are actually reducing churn.

---

## Connect With Me

**Winner Donald**

📧 [winnerdonald158@gmail.com](mailto:winnerdonald158@gmail.com)

💻 GitHub

🔗 LinkedIn: [www.linkedin.com/in/winner-donald](http://www.linkedin.com/in/winner-donald)

📍 Abuja, Nigeria

