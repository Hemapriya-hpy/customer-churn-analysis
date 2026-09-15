# Customer Churn & Retention Analysis

## 📌 Project Objective
Developed an end-to-end Python pipeline using Pandas and Seaborn to clean historical client records, isolate key business cancellation drivers, and provide data-backed customer retention strategies.

## 📊 Data Source
The dataset used for this analysis is the industry-standard **Telco Customer Churn** dataset provided by IBM. To maintain repository lightweight best practices, the pipeline streams the data directly via a secure remote URL instead of hosting local CSV files.

## 🛠️ Tech Stack & Skills
- **Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
- **Concepts:** Data Cleaning, Exploratory Data Analysis (EDA), Descriptive Statistics, Data Visualization

## 🔍 Key Insights Discovered
- **Contract Risk:** Month-to-month contract users exhibit a drastically higher churn rate compared to long-term contract tiers.
- **Financial Pain Points:** Churned customers maintain a significantly higher average monthly bill, proving pricing is a core friction point.
- **Service Vulnerabilities:** Fiber Optic subscribers drop out at higher rates than DSL users, pointing to potential service stability or localized onboarding issues.
- **Critical Onboarding Window:** A massive spike in churn occurs within the first 0 to 5 months of tenure, identifying the critical window for proactive customer success intervention.

## 💡 Strategic Business Recommendations
1. **Contract Incentives:** Launch a targeted campaign offering financial incentives (e.g., a one-month credit) to transition high-risk Month-to-Month customers onto stable 1-Year or 2-Year contracts.
2. **Onboarding Playbook:** Establish a proactive "Customer Success Check-In" pipeline during months 1 through 3 to address early friction points and decrease early-stage dropouts.
3. **Fiber Optic Audit:** Collaborate with product and pricing teams to evaluate if the current premium pricing for Fiber Optic lines matches the localized connection quality.
