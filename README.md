# Bank Marketing Campaign Analysis

A business analytics project analyzing customer behaviour and marketing campaign data to identify factors associated with term-deposit subscription and support more targeted campaign strategies.

---

## Project Overview

Banks use marketing campaigns to encourage existing and potential customers to subscribe to financial products such as term deposits. However, customers do not respond to these campaigns in the same way.

This project analyzes the Bank Marketing dataset to understand why some customers subscribe to term deposits while others do not, and to identify customer groups that are more likely to respond positively to marketing campaigns.

The analysis combines exploratory data analysis, customer segmentation, and predictive modelling to translate customer behaviour into practical business insights.

---

## Business Problem

The bank wants to improve the effectiveness of its term-deposit marketing campaigns.

Rather than approaching all customers using the same strategy, the analysis focuses on two key questions:

1. Why do some customers subscribe to term deposits while others do not?
2. Which customer groups are more likely to respond positively to marketing campaigns?

---

## Business Objectives

The analysis aims to:

- Understand differences between customers who subscribe and those who do not.
- Identify customer segments with higher or lower subscription rates.
- Examine the relationship between customer characteristics and campaign outcomes.
- Identify factors associated with term-deposit subscription.
- Translate the findings into actionable marketing recommendations.

---

## Dataset

The Bank Marketing dataset contains **11,162 customer records and 17 variables**.

The variables cover:

- **Demographics:** age, job, marital status, and education
- **Financial information:** balance, default, housing loan, and personal loan
- **Campaign information:** contact method, campaign contacts, previous contacts, and previous campaign outcome
- **Target variable:** deposit

The `deposit` variable indicates whether the customer subscribed to a term deposit.

---

## Analysis Process

The analysis followed a structured business analytics approach:

### 1. Dataset Overview

The dataset structure, dimensions, data types, and missing values were assessed.

- 11,162 rows
- 17 columns
- 7 numerical variables
- 10 categorical variables
- No missing values identified

### 2. Exploratory Data Analysis

Customer characteristics and campaign variables were explored to understand differences between subscribers and non-subscribers.

### 3. Customer Segmentation

Subscription rates were compared across:

- Age groups
- Job types
- Education levels
- Marital status

### 4. Key Driver Analysis

Subscription rates were also compared across:

- Previous campaign outcomes
- Housing loans
- Personal loans
- Contact methods

Subscriber and non-subscriber averages were also compared across variables such as balance, call duration, campaign contacts, and previous contacts.

### 5. Predictive Modelling

A logistic regression model was developed to identify variables associated with term-deposit subscription and quantify their relationship using odds ratios.

The model achieved:

- **ROC-AUC: 0.907**
- **Accuracy: 83%**

---

## Key Findings

### Previous Campaign History

Customers with a previous successful campaign outcome recorded a **91.3% subscription rate**, compared with **40.7%** among customers whose previous outcome was unknown.

Previous campaign success was also associated with approximately **8.9× higher odds of subscription**.

This was the strongest positive signal identified in the analysis.

### Financial Commitments

Customers without housing loans recorded a **57.0% subscription rate**, compared with **36.6%** among customers with housing loans.

Customers without personal loans recorded a **49.5% subscription rate**, compared with **33.2%** among customers with personal loans.

### Contact Method

Customers reached through cellular contact recorded a **54.3% subscription rate**, compared with **22.6%** among customers with an unknown contact method.

### Customer Engagement

Subscribers had an average call duration of **537 seconds**, compared with **223 seconds** for non-subscribers.

Call duration was associated with approximately **6.4× higher odds of subscription**. However, it should be interpreted as an indicator of customer engagement rather than a factor known before the call.

### High-Response Customer Groups

Some customer groups recorded notably higher subscription rates:

- **60+ age group — 76.92%**
- **Students — 74.72%**
- **Retired — 66.32%**
- **Tertiary education — 54.11%**
- **Single customers — 54.35%**

---

## Business Insights

The analysis suggests that:

- Previous customer behaviour provides a strong signal for future campaign response.
- Certain customer segments demonstrate significantly higher subscription rates.
- Existing financial commitments are associated with lower subscription rates.
- Reliable customer contact information and meaningful engagement are important for campaign effectiveness.
- Predictive analytics can support more efficient campaign prioritization.

---

## Recommendations

Based on the analysis, the following actions are recommended:

1. **Prioritize customers with previous campaign success** when planning future campaigns.

2. **Target high-response customer segments** with tailored messaging and offers.

3. **Improve customer contact information** to support more effective campaign outreach.

4. **Test tailored approaches for lower-response groups**, particularly customers with existing financial commitments.

5. **Introduce predictive campaign prioritization** by using customer scores to identify customers with higher likelihood of subscription.

---

## Project Files

- 📓 [View Python Analysis Notebook](https://colab.research.google.com/drive/1OKMyP0M-Jr795bQDLGDejOxKrQ6W5Qo-?usp=sharing)
- 📄 `Bank_Marketing_Term_Deposit_Case_Study.pdf` — Detailed business case study, findings, insights, and recommendations.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Logistic Regression
- Google Colab

---

## About Me

**Precious Ogede**

**Data Analyst** focused on transforming business data into actionable insights through analytics, business intelligence, and data visualization.

**Skills:** Python • Pandas • SQL • Power BI • Tableau • Excel • Business Analytics • Data Visualization
