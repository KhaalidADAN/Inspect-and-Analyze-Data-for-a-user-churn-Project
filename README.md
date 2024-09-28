# Waze App User Churn Prevention Project

## Project Overview
This project aims to identify key factors driving user churn in the Waze app and develop strategies to reduce monthly churn. Churn is defined as users who either uninstall the app or stop using it. Our preliminary analysis focuses on understanding user behavior patterns and variables that correlate with churn.

## Business Understanding
The Waze team wants to reduce user churn to improve overall app growth. By identifying behavioral patterns of users who are likely to churn, targeted strategies can be deployed to retain them.

**Stakeholders:**
- Waze App Development Team
- Marketing and User Retention Teams

The goal is to use insights from data to prevent churn and retain more users, especially those who seem to use the app more frequently.

## Data Understanding
The dataset includes:
- **Churn Distribution:** 82% retained users and 18% churned users.
- **Variables:** 12 unique variables, including user activity metrics like the number of drives, kilometers driven, and days active.
- **Missing Data:** Missing data in the label column for 700 entries, but the missingness does not appear non-random.

### Key Insights:
- Churned users averaged **~3 more drives** in the last month compared to retained users.
- Retained users used the app on **twice as many days** as churned users.
- Churned users drove **240% more kilometers** per drive-day than retained users.

### Data Limitations:
- The data may represent super-drivers and not typical Waze users. More granular data is required to fully understand their unique needs.

## Modeling and Evaluation
We are currently conducting exploratory data analysis (EDA) and gathering insights for future model development. The next step will be to visualize the data to guide project decisions and modeling efforts.

## Conclusion
The preliminary analysis provides a strong foundation for identifying patterns of churn among heavy app users. Our findings suggest that super-drivers churn despite their frequent use, possibly due to unmet needs.

## Next Steps:
- **Collect More Data:** Focus on the behavior of super-drivers to understand why they churn despite heavy usage.
- **Conduct EDA:** Develop visualizations to capture key insights and inform model-building.
- **Model Development:** Build predictive models to identify users at high risk of churning.
