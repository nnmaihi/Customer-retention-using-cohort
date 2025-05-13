# Customer-retention-using-cohort
### Objective
The goal of this project is to evaluate customer retention behavior in a mobile wallet platform using cohort analysis. The analysis focuses on understanding churn patterns, identifying high-value users, and uncovering category-specific trends to inform strategies for improving user retention and engagement.

## Data Source
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/harunrai/digital-wallet-transactions?resource=download), containing anonymized mobile wallet transaction records with attributes such as timestamps, user IDs, transaction amounts, product categories, and payment methods.

### Project Content
Importing Libraries and Data: Load necessary Python libraries and import the dataset for analysis.

EDA:
- Standardize datetime, summary statistics, data checks: Ensure data consistency and completeness.
- Monthly user activity & volume: Visualize trends in user acquisition and transaction frequency.
- Transaction amount distribution: Examine value spread and detect outliers.
- Top product categories by total transaction amount: Identify high-revenue categories.

Cohort Analysis
- Customer Retention by Month: Track unique users by signup month and measure their retention over time.
- Retention Rate by Month: Visualize user return rates across cohorts.
- Transaction Amount Retention: Analyze how average spending evolves across retention months
- Category-Specific Retention: Compare retention patterns for top revenue-generating product categories.

### Recommendations
- Improve customer experience in-app: Streamline onboarding, reduce friction, and enhance in-app usability.
- Focus on high-value users & recurring categories: Prioritize segments that show higher retention and consistent transaction value.
- Launch trigger-based campaigns: Engage users at risk of churn with personalized, timely offers to increase return visits.
