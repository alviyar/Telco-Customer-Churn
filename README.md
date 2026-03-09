# 📊Customer Churn & Retention Analysis
<img width="1367" height="780" alt="image" src="https://github.com/user-attachments/assets/453e26f8-a228-4631-9d7f-6b45f173788e" />

**A Strategic Operational Case Study**  
🔎 Project Objective  
This project analyzes customer attrition patterns to evaluate how service quality, billing friction, and contract structures impact long-term revenue. The goal is to identify high-risk customer segments and provide data-driven strategies to reduce the 26.54% churn rate.

📁 **Dataset & Scope**  
Source: Industry-standard Telco Customer Churn dataset(Kaggle).

Scope: Contract types, internet service tiers, payment methods, monthly charges, and technical support status.

Total Customers: 7,000

Total Churned: 2,000

Churn Rate: 26.54%

Avg Monthly Charges: ₹64.76

📌 **Key KPIs**  
Customer Base: 7K total subscribers.

Revenue at Risk: Churned customers account for an average of ₹74/month, significantly higher than the ₹61/month average of retained customers.

Critical Churn Window: 0–12 months (First-year tenure).

Primary Risk Factor: Month-to-month contracting.

📊 **Key Insights**  
1️⃣ Tenure is the Strongest Predictor of Loyalty
Retention increases exponentially with time.

0–1 Year: 47.44% Churn (The "Danger Zone").

4+ Years: 9.51% Churn (The "Loyalty Zone").

Insight: The first 12 months are the most critical for customer success interventions.

2️⃣ Contract Structure Dictates Revenue Stability
The flexibility of short-term plans comes at a massive cost to retention.

Month-to-month: 42.71% Churn Rate.

Two-year: 2.83% Churn Rate.

Insight: Moving customers from monthly to annual plans reduces churn risk by over 15x.

3️⃣ Technical Support as a Retention Engine
Availability of assistance significantly lowers the probability of cancellation.

No Tech Support: 41.64% Churn.

With Tech Support: 15.17% Churn.

Insight: Support is not just a cost center; it is a vital defensive strategy for revenue.

4️⃣ Payment Friction and Pricing Sensitivity
Electronic Check: Highest churn rate at 45.29%, compared to ~15% for automated methods (Credit Card/Bank Transfer).

Price Point: Churned customers paid 21% more on average per month than retained customers.

Insight: High monthly costs combined with manual payment hurdles drive customers to competitors.

🧠 **Strategic Recommendations**  
Migrate to Automation: Incentivize the switch from Electronic Checks to Automated Billing to reduce involuntary churn.

Bundle Tech Support: Include "Basic Tech Support" in high-tier Fiber Optic plans to anchor premium customers.

The "Year 1" Playbook: Implement a specialized onboarding and discount program for customers in their first 12 months.

Contract Incentives: Offer a "13th Month Free" or similar rewards for migrating from Month-to-month to 1-Year or 2-Year agreements.

🛠 **Technical Pipeline**  
SQL: Used for data aggregation, tenure grouping, and segmenting high-value vs. high-risk accounts.

Python (Jupyter): Conducted Exploratory Data Analysis (EDA) to find correlations between service types and churn.

Power BI: Built an interactive executive dashboard for real-time KPI monitoring.

📈 Conclusion
This analysis demonstrates that churn is not random; it is driven by contract type, payment friction, and early-tenure engagement. By optimizing the onboarding experience and incentivizing long-term commitments, the organization can significantly stabilize its recurring revenue.
