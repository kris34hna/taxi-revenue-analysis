# Maximizing Revenue for Taxi Cab Drivers Through Payment Type Analysis

## Project Overview
This project analyzes NYC Taxi Trip data to uncover insights about how payment methods
impact fare amounts and driver revenue. Using statistical analysis and hypothesis testing,
we determine whether encouraging card payments can maximize taxi driver earnings.

---

## Problem Statement
In the fast-paced taxi booking sector, maximizing revenue is essential for long-term 
success and driver happiness. This research focuses on the relationship between 
payment type and fare amount to determine whether payment methods influence fare pricing.

---

## Research Questions
- Is there a relationship between total fare amount and payment type?
- Can we nudge customers towards payment methods that generate higher revenue
  for drivers, without negatively impacting customer experience?

## Detailed Insights

### 1. Payment Type Preference
- Card payments account for **67.5%** of all transactions
- Cash payments account for only **32.5%**
- Customers strongly prefer card over cash possibly due to convenience and security

### 2. Fare Amount Insights
| Payment Type | Mean Fare | Standard Deviation |
|-------------|-----------|-------------------|
| Card |         $13.70           $6.5 
| Cash |         $12.25           $6.2 
- Card users pay **$1.45 more** on average than cash users
- Suggests customers prefer card when fare amount is high

### 3. Trip Distance Insights
| Payment Type | Mean Distance | Standard Deviation |
|-------------|--------------|-------------------|
| Card |         3.23 miles         2.32 
| Cash |         2.80 miles         2.23 
- Card users travel **0.43 miles more** on average
- Longer trips = higher fare = customer prefers card

### 4. Passenger Count Insights
| Passenger Count | Card % | Cash % |
|----------------|--------|--------|
| 1 (Solo) | 40% | 20% |
| 2 (Pair) | 14% | 7% |
| 3        |  5% | 2% |
| 4        |  3% | 1% |
| 5        |  5% | 2% |
- Solo riders are the **biggest customer segment** for both payment types
- As group size increases, number of trips **decreases** for both
- Card payments dominate **across all passenger counts**

### 5. Hypothesis Testing Conclusion
- T-statistic of **165.5** and P-value **< 0.05**
- We **reject the null hypothesis**
- There is a **statistically significant difference** in fare amount
  between card and cash payments
- Card payments generate **higher revenue** for drivers

- There is a **statistically significant difference** in fare amount
  between card and cash payments
- Card payments generate **higher revenue** for drivers
