# Online Advertising Effectiveness Study - A/B Testing Analysis

## 1. Overview

Online advertising plays a key role in driving customer engagement and revenue, but its effectiveness depends not only on whether ads are shown, but also on how often and when they are displayed.

This project analyzes the impact of online advertisements on purchase behavior using data from an A/B test with 20,000 users. Customers were shown either an advertisement (Ad) or a public service announcement (PSA) over a 31-day period, allowing for a direct comparison of their effects.

The analysis focuses on four main questions:

Are users exposed to ads more likely to make a purchase than those exposed to PSAs?

How does ad exposure frequency relate to purchase behavior?

Do purchase rates vary by the time of peak ad exposure?

Do ads and PSAs differ in how purchase behavior changes with increased exposure?

**The goal is to provide a clear evaluation of advertising effectiveness and to extract practical insights into how ad exposure influences purchasing behavior.
**---

## 2. Dataset

### 2.1 Source
The dataset used for this analysis is available on Kaggle:  
[Online Advertising Effectiveness Study - A/B Testing](https://www.kaggle.com/datasets/farhadzeynalli/online-advertising-effectiveness-study-ab-testing?resource=download)

### 2.2 Dataset Structure
The dataset contains the following columns:  

- customerID: Unique identifier for each customer.  
- test_group: `'ad'` (advertisement) or `'psa'` (public service announcement).  
- made_purchase: Boolean indicating whether the customer made a purchase after viewing the advertisement.  
- days_with_most_ads: The day of the month the customer saw the most ads.  
- peak_ad_hours: The hour of the day when the customer saw the most ads.  
- ad_count: Total number of ads shown to the customer.  

---

## 3. Analysis

### 3.1 Tools Used
- Python (pandas, numpy)  
- Jupyter Notebook  

### 3.2 Structure of the Analysis
1. Introduction
2. Data Source
3. Data Preparation
4. Data Analysis
   4.1 Analysis of Ad Exposure at Group Level (Ad vs. PSA)
   4.2 Analysis of Ad Exposure at Individual Ad Level
   4.3 Ad Exposure at Peak Ad Hours Level
   4.4 Purchase Rates by Exposure Level: Ads vs. PSA
5. Conclusion and Outlook


### 3.3 Key Findings
- Users exposed to advertisements were significantly more likely to make a purchase than users exposed to public service announcements (PSAs). The ad group’s purchase rate was more than twice as high, and this difference was statistically significant.

- Increasing ad exposure was associated with a small increase in purchase likelihood, but only up to a moderate level. Beyond this point, additional exposure did not consistently lead to higher purchase rates.

- PSA exposure showed little to no effect on purchasing behavior, regardless of how often users were exposed.

- Purchase rates varied substantially across early hours of the day due to small sample sizes, while later hours showed more stable and reliable patterns. Time-of-day effects should therefore be interpreted with caution.

Overall, the analysis indicates that advertising is effective in increasing purchases compared to PSAs, but simply increasing the number of ad impressions provides limited additional benefit beyond moderate exposure levels.
---

## 4. Usage / Installation

1. Clone the repository.  
2. Install required Python libraries (pandas, numpy)
3. Run the Jupyter Notebook for analysis.

---

## 5. Contact
For questions or contributions, please contact me through GitHub.
Thank you.
