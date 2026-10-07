# 📊Subscription-Cohort-Analysis-Data

An interactive Power BI dashboard for analyzing subscription activity, customer behavior, payment status, and cancellation patterns.

## 📌 Project Overview

This project analyzes subscription data to understand:

- Customer acquisition and subscription activity
- Active vs cancelled subscriptions
- Monthly subscription trends
- Monthly cancellation trends
- Paid vs unpaid subscriptions
- Cancellation behavior by payment status
- Customer subscription patterns

The project was created using Power BI with data transformation in Power Query and analysis using DAX.

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze overall subscription performance.
2. Understand customer subscription behavior.
3. Track monthly subscription and cancellation trends.
4. Compare paid and unpaid subscriptions.
5. Analyze cancellation rates by payment status.
6. Build an interactive dashboard for business-level insights.

---

## 📂 Dataset

The dataset contains subscription-level records with the following fields:

| Column | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `created_date` | Subscription creation date |
| `canceled_date` | Subscription cancellation date |
| `subscription_cost` | Subscription cost |
| `subscription_interval` | Subscription billing interval |
| `was_subscription_paid` | Indicates whether the subscription was paid |

### Dataset Summary

- **Total subscription records:** 3,069
- **Unique customers:** 2,877
- **Active subscriptions:** 1,065
- **Cancelled subscriptions:** 2,004
- **Paid subscriptions:** 2,936
- **Unpaid subscriptions:** 133

> Note: Subscription counts refer to subscription records, while customer counts refer to unique customers.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Visualization**
- **Data Modeling**

---

## 🔄 Data Preparation

The data was prepared using Power Query.

Major transformations included:

- Created subscription status
- Created monthly date fields
- Calculated subscription duration
- Created payment status
- Created customer-level summary table
- Identified one-time and repeat customers
- Created customer cohort month
- Established relationships between customer and subscription tables

---

## 🧩 Data Model

The project uses a simple relational model:

```text
Customers
    │
    │ 1 : *
    ▼
Subscriptions
<img width="1322" height="745" alt="Dashboard" src="https://github.com/user-attachments/assets/f6a22a5f-e6cc-4916-a95a-b50fae314927" />
