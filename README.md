# Customer Lifetime Value & Churn Analytics

End-to-end customer analytics project using the **Telco Customer Churn dataset** to analyze customer churn, estimate Customer Lifetime Value (CLV), and identify high-value and high-risk customer segments.

## 🎯 Business Objective

Customer churn directly affects recurring revenue and long-term customer value. This project analyzes customer demographics, services, contract information, tenure, and billing behavior to understand the drivers of churn and identify customers who may require retention efforts.

The analysis aims to answer:

- What factors are associated with customer churn?
- Which customer segments have the highest churn rates?
- How does customer tenure relate to churn?
- Which customers have the highest estimated CLV?
- Are high-value customers at risk of churning?
- Which customer segments should be prioritized for retention?

## 📂 Dataset

The analysis uses the **Telco Customer Churn dataset**, containing customer-level information such as:

- Customer demographics
- Tenure
- Contract type
- Internet and phone services
- Payment method
- Monthly charges
- Total charges
- Churn status

## 🛠️ Tools & Technologies

- **PostgreSQL / SQL** – Data querying and customer segmentation
- **Python** – Data cleaning, exploratory analysis and CLV analysis
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Power BI** – Interactive dashboard and business reporting

## 📊 Analysis

### Customer Churn Analysis

- Overall churn rate
- Churn by contract type
- Churn by tenure
- Churn by payment method
- Churn by internet service
- Churn by customer segment

### Customer Lifetime Value Analysis

- CLV estimation
- CLV by customer segment
- Identification of high-value customers
- Relationship between CLV and churn
- High-value, high-risk customer identification

## 💡 Key Insights

Key findings will be documented after completing the analysis.

## 🚀 Business Recommendations

Based on the analysis, recommendations will focus on:

- Prioritizing high-value customers at risk of churn
- Improving retention among high-risk segments
- Understanding factors contributing to early-stage churn
- Developing targeted customer retention strategies

## 📈 Power BI Dashboard

The dashboard will provide an interactive view of:

- Churn KPIs
- Customer segments
- CLV distribution
- Churn drivers
- High-value customers
- High-risk customer segments

## 📁 Repository Structure

```text
Data/       → Telco Customer Churn dataset
SQL/        → PostgreSQL queries and analysis
Analysis/   → Python/Jupyter Notebook analysis
Visuals/    → Charts and visualizations
README.md   → Project documentation
