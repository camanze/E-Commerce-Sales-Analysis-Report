# E-Commerce-Sales-Analysis-Report

**INTRODUCTION:**

In the rapidly evolving world of e-commerce and digital retail, data plays a critical role in driving strategic decisions. This project presents a detailed analysis of an online sales dataset, offering valuable insights into sales trends, customer behavior, product performance, and operational efficiency. The dataset encapsulates anonymized transactional data from various countries and product categories, providing a robust foundation for extracting actionable intelligence. The goal of this analysis is to help stakeholders improve sales performance, enhance customer satisfaction, and streamline order management processes using a data-driven approach.

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

### **ANALYSIS AND VISUALIZATION USING POWER BI**

I used Power BI to create interactive and insightful dashboards. The report is organized into three distinct dashboards to ensure a clear and comprehensive presentation of the findings.

