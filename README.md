# **🦎 CLV Prediction for Customer Retention Strategy Optimization**
## **Business problem**
Insurance companies have very limited budget for marketing. Optimization needs to be done on customer retention campaign/strategies to prioritize maintaining valuable customers. Customer Lifetime Value (CLV) can be used to allocate marketing budget to customers that will bring the highest revenue.

**Goal**: Determine customer's lifetime value using their profile data to identify high-value customers.\
**Analytical Approach**: Develop an accurate regression model trained using historical customer profile data to predict Customer Lifetime Value.

### **Objectives**
1. Develop a machine learning model that accurately predicts CLV using available customer features.
2. Map out feature importance to explain which features afffect CLV the most and how they can guide business actions.

### **Deliverables**
1. Notebook (eda, cleaning/preprocessing, feature engineering/selection, modelling, evaluation)
2. Slide deck
3. streamlit prototype
4. github README and reproducability tutorial

----

## **Mock-Case Study**
**GAICO** is a leading American vehicle insurance company offering a range of auto coverage products across multiple customer segments. In 2019, GAICO's marketing team launched a campaign to improve customer retention and optimize marketing budget by identifying high-value customers that generate higher lifetime revenue and are more likely to stay with GAICO. They tasked the analytics team to develop a predictive model for Customer Lifetime Value (CLV) using historical customer profile data.

**Stakeholder**: GAICO's Marketing team\
**My Role**: GAICO Analytics team

----

### **Metric Selection**
- **RMSE (Root Mean-Squared Error)**: Good to evaluate models that wants to achieve high accuracy. A good fit for financial, pricing, forecasting contexts.
- **R^2**: Captures proportion of variance
- **MAPE (Mean Absolute Percentage Error)**: Easily interpretable percentage metric for stakeholders.

### **Data Dictionary**
Data used is a customer profile data from an American vehicle insurance company in 2019. One row represents a single customer.

| Feature | Type | Description 
|---|---|---|
| Vehicle Class | Categorical (Nominal) | Type of vehicle insured. |
| Coverage | Categorical (Ordinal) | Coverage tiers ("Basic", "Extended", "Premium"). |
| Renew Offer Type | Categorical (Nominal) | Type of renewal offer presented. |
| EmploymentStatus | Categorical (Nominal) | Customer's employment status (“Employed”, "Medical Leave", “Unemployed”, “Retired”, “Disabled”). |
| Marital Status | Categorical (Nominal) | Customer's status (“Married”, “Single”, “Divorced”). |
| Education | Categorical (Ordinal) |Educational background ("Highschool or below", "College", "Bachelor", "Master", "Doctor"). |
| Number of Policies | Numerical (Float) | Number of active insurance policies the customer holds. |
| Monthly Premium Auto | Numerical (Float) | The amount the customer pays monthly for auto insurance in USD. |
| Total Claim Amount | Numerical (Float) | The total dollar amount of claims made by the customer in USD. |
| Income | Numerical (Float) | Customer's annual income in USD |
| Customer Lifetime Value | Numerical (Float) | Target value. Projected total revenue a customer will bring in USD. |
