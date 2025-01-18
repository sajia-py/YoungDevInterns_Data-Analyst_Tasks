# **Business Performance Analysis - 2011**

## **Overview**
This analysis addresses four key questions from the CEO and CMO, focusing on revenue trends, customer insights, and geographic sales performance. The dataset was thoroughly prepared and analyzed to ensure accurate, actionable insights.

---

## **Process**
### **1. Data Loading**
- Imported the dataset into the analysis tool.
- Ensured correct formatting of critical fields: Invoice Date, Quantity, Unit Price, and Customer ID.

### **2. Data Cleaning**
- Removed invalid or missing data, including:
  - Records with missing Customer IDs.
  - Entries with negative quantities.
- Ensured data accuracy for meaningful insights.

### **3. Data Preparation**
- Created a **Revenue** field by multiplying `Quantity` by `Unit Price`.
- Grouped data by relevant dimensions:
  - Monthly aggregation for trends.
  - Country-level grouping for regional analysis.
  - Customer-specific filtering for top customer insights.
- Applied filters to exclude unwanted data, such as the United Kingdom and missing values.

---

## **Findings**
### **1. Monthly Revenue Trends in 2011**
- **Visual:** Line Chart
- **Insights:**
  - Clear monthly revenue trends with peaks during November.
  - Insights guide strategic planning and revenue forecasting.

### **2. Revenue and Quantity by Country**
- **Visual:** Side-by-Side Bar Chart
- **Insights:**
  - Top 10 countries (excluding the UK) analyzed for revenue and quantity.
  - United Kingdom identified as top contributors, offering opportunities for targeted campaigns.

### **3. Top 10 Customers by Revenue**
- **Visual:** Vertical Bar Chart
- **Insights:**
  - Top 10 customers identified and sorted by descending revenue.
  - Customer ID 14646 highlighted as the largest contributor, with opportunities for loyalty programs and upselling.

### **4. Global Sales Distribution**
- **Visual:** Map Chart
- **Insights:**
  - Total units sold visualized globally, excluding the UK.
  - Key markets identified in France, while Germany suggests room for growth.

---

## **Recommendations**
- **Focus Marketing Efforts:** Prioritize high-performing countries and strategize expansion in underperforming regions.
- **Customer Retention:** Develop loyalty programs for top customers to drive repeat business.
- **Geographic Expansion:** Explore new campaigns in regions with potential for growth.

---

## **Conclusion**
This analysis provides a comprehensive view of business performance in 2011, highlighting key trends and actionable insights. By implementing the recommendations, the company can optimize its strategies for growth and customer retention.
