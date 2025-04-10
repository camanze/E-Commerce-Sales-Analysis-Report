# Sales-Analysis-Report

**INTRODUCTION:**

In the rapidly evolving world of e-commerce and digital retail, data plays a critical role in driving strategic decisions. This project presents a detailed analysis of an online sales dataset, offering valuable insights into sales trends, customer behavior, product performance, and operational efficiency. The dataset encapsulates anonymized transactional data from various countries and product categories, providing a robust foundation for extracting actionable intelligence. This report provides an end-to-end breakdown of the dataset and the analytical approach, covering financial performance, product demand, return rates, and the impact of discounts, payment methods, and shipment providers on customer satisfaction.

The goal of this analysis is to help stakeholders improve sales performance, enhance customer satisfaction, and streamline order management processes using a data-driven approach.

**OBJECTIVE:**

- Identify top-performing products and customer segments.

- Assess the impact of payment methods and shipment providers on sales.

- Highlight operational inefficiencies and recommend process improvements.

- Diagnose operational bottlenecks (e.g., 98.17% return rate anomalies).

- Provide actionable strategies to improve profitability and data integrity.


### **DATA DESCRIPTION AND COLLECTION:**

The dataset used for this project was sourced from Kaggle. [Click here to access it.](https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset) The dataset comprises over 45 thousand anonymized transactions with the following key features;

- **InvoiceNo:**	Unique order identifier
  
- **CustomerID:**	Anonymized customer ID
  
- **Category:**	Product category (e.g., Stationery, Electronics)
  
- **Description:**	Product details (e.g., "USB Cable," "Office Chair")
  
- **Country:**	Customer location (e.g., Germany, Australia)
  
- **Quantity:**	Units sold (negative values indicate returns)
  
- **UnitPrice:**	Price per unit
  
- **SalesChannel:**	Order origin (In-store/Online)
  
- **ReturnStatus:**	Whether the item was returned
  
- **PaymentMethod:**	Payment type (PayPal, Credit Card, Bank Transfer)

### **Data Structure**

- **Products:** 5 categories (Furniture, Accessories, Electronics, Stationery, Apparel).

- **Geographies:** 12 countries, including the US, UK, Sweden, and Germany.

- **Operational Data:** Shipment providers (FedEx, Royal Mail), return statuses, and payment methods.

### **Critical Data Quality Notes**

- **Inconsistencies:** Negative quantities (e.g., -13 units) and prices suggest potential data entry errors or returns, and misspelled fields (“paypall”).

### **Key Data Exploration and Cleaning Steps:**

Initial exploration of the dataset revealed that some columns contained values in inconsistent formats, which required standardization to ensure accurate analysis. These were taken care of.

The negative quantity and price values were replaced with absolute values, as they are considered as imput errors.

A Date table was created and marked as the date table for the project, after establishing a relationship between the Date table and the Sales table.

Another table was created for Measures and intereting percentage month-on-month metrics were calculated using measures for the Total Sales, Total orders, Total Customers and Average Order Value.

This diverse dataset allows for rich, multidimensional analysis across several business functions—from sales forecasting to operational planning.

### **ANALYSIS AND VISUALIZATION USING POWER BI**

I used Power BI to create interactive and insightful dashboards to uncover patterns and trends. The report is organized into three distinct dashboards to ensure a clear and comprehensive presentation of the findings. These dashboards feature:

* **Overall Sales Performance:** Including total revenue, number of orders, and average order value.

* **Customer Insights:** Segmenting customers by country, purchase frequency, and return behavior.

* **Product Category Analysis:** Evaluating revenue contributions and order volume by category.

* **Geographic Trends:** Mapping sales distribution by country to identify high-performing markets.

* **Shipment Provider Performance:** Comparing the cost of shipping orders across DHL, FedEx, UPS, and Royal Mail.

* **Return Trends:** Monitoring return percentages to understand areas for improvement in product quality or customer experience.

* **Payment Preferences:** Analyzing how different payment methods correlate with order volume and returns.

Each dashboard was designed with a focus on clarity, actionability, and dynamic filtering to support ad-hoc decision-making. 

![Sales Overview](https://github.com/user-attachments/assets/4b30fd3a-eb61-40da-80c8-25f9442bdc6a)

### **KEY FINDINGS**

**Sales Channel Distribution:** Online sales were dominant, showing higher reach and repeat purchases. However, in-store channels attract higher-value purchases, while online channels drive volume.

**Product Category Leaders:** Furniture and accessories were among the top-performing categories.

**Top Markets:** Countries like Belgium, Germany and the United Kingdom emerged as key revenue contributors.

**Operational Efficiency:** Shipment providers like FedEx and Royal Mail, handled the highest number of orders with varying total shipping costs across providers.

**Customer Satisfaction:** Low return rates across most product categories suggest high customer satisfaction and efficient fulfillment processes.

**Payment Insights:** Bank Transfers and PayPal emerged as preferred payment methods, indicating customer trust in digital payment solutions.


### **RECOMMENDATIONS**

1. **Data Quality Overhaul:**

   - Implement automated validation to flag negative values and standardize fields (e.g., “PayPal”).

2. **Operational Adjustments:**

   - Negotiate bulk shipping rates with FedEx/Royal Mail to reduce costs.

   - Introduce loyalty rewards for Credit Card users to boost AOV.

3. **Product Strategy:**

   - Create product bundles (e.g., Stationery with Furniture/Electronics) to increase margins.

4. **Tech Investments:**

   - Develop a real-time Business Intelligence dashboard to monitor business data KPIs.

   - Train staff on data entry protocols to minimize errors.


### **CONCLUSION**

This analysis highlights the value of using business intelligence tools to interpret sales data in a fast-moving e-commerce environment. By transforming raw transactional data into meaningful insights, the analysis identifies key strengths such as product performance and geographic demand while also pointing to opportunities for improvement in logistics and payment experiences.

The insights derived can directly support business strategies around product restocking, shipment optimization, and customer engagement.
