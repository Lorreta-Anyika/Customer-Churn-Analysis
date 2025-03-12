# **Customer Churn Analysis**

## **Project Overview**  
Customer churn is a major challenge for businesses, especially in the telecom industry, where losing customers translates to revenue loss. Studies suggest that acquiring a new customer can be **5–7 times more expensive** than retaining an existing one.  

This project analyzes a telecom customer churn dataset to uncover trends, identify high-risk customers, and suggest actionable retention strategies.

Here's a snapshot of the dashboard:
![image](https://github.com/user-attachments/assets/1b8f1891-70f6-4070-b5b1-d440ca3680b9)


---

## **Data Source**  
The dataset contains **50,000+ rows** of telecom customer data, including:  
- Customer tenure and monthly usage  
- Call center interactions  
- Geographic location  
- Churn status (no vs. yes)  

---

## **Tools Used**  
- **Microsoft Excel**  
  - Power Query for data cleaning  
  - PivotTables for segmentation  
  - PivotCharts for visualization  
- **Data Visualization**: Heatmaps, bar charts, pie charts  
- **Interactive Dashboard**: Slicers and timeline filters  

---

## **Data Cleaning and Preparation**  
Using **Power Query**, the dataset was prepped efficiently:  
✅ **Duplicates & Blanks Removed**  
✅ **Missing Values Handled**  
✅ **Data Standardized**  

**🔎 Trial & Error:**  
- Initially used Excel formulas but crashed at **10K+ rows**  
- Switched to Power Query, reducing load time by **70%**  

---

## **Exploratory Data Analysis (EDA)**  
Key segmentation strategies included:  
- **Binning Monthly Minutes** (adjusted to 200/500 thresholds for clearer patterns)  
- **Grouping Customer Call Center Interactions**  
- **Segmenting Churn Rate by Location**  

---

## **Data Analysis**  
📊 **Key Insights:**  
- **Churn Rate**: 23% of customers left the service.  
- **Call Patterns**: Churned customers made significantly more support calls—an **early warning sign** of dissatisfaction.  
- **Usage Trends**: Monthly usage was similar between churned and retained customers, suggesting **customer experience matters more than usage**.  
- **Top Churn Locations**: High churn areas included **DALLA214 (23 churns)** and **NYCBRO917 (20 churns)**.  

---

## **PivotCharts & Interactive Dashboard**  
The final dashboard provided **actionable insights** using:  
✅ **Summary Metrics**: Total churn rate, revenue impact  
✅ **Geographic Heatmap**: Visualizing churn hotspots  
✅ **Usage vs. Retention Scatter Plot**  
✅ **Churn Driver Breakdown** (Income, Dropped Calls, Location)  

**🔎 Trial & Error:**  
- The initial dashboard was static. Added **slicers & timeline filters** for **interactivity** based on feedback.  

---

## **Results & Findings**  
🚀 **How This Helps Telecom Companies:**  
✔️ **Early Detection**: Identify at-risk customers by tracking high support interactions.  
✔️ **Personalized Plans**: Offer targeted incentives in high-churn areas.  
✔️ **Proactive Support**: Customers making **5+ support calls** should receive **VIP-level assistance**.  

---

## **Recommendations**  
🔹 **Implement proactive customer support** for users making frequent service calls.  
🔹 **Target high-churn locations** with retention campaigns and improved service quality.  
🔹 **Introduce loyalty programs** to keep long-tenured customers engaged.  

---

## **Limitations**  
- The dataset lacks demographic details that could refine churn predictions.  
- External factors (e.g., competitor promotions) were not included in the analysis.  
