
## 1. **Project Title / Headline**

**UPI Transactions Dashboard – 2024 Analysis**


## 2. **Short Description / Purpose**

This Power BI dashboard visualizes and analyzes UPI (Unified Payments Interface) transactions for the year 2024. It provides dynamic insights into transaction patterns, user demographics, payment behaviors, and balances to support data-driven decisions for financial institutions and digital payment platforms.



## 3. **Tech Stack**

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main platform for developing interactive data visualizations and reports
* 🧩 **Power Query** – Used for importing, transforming, and cleaning the transaction data
* 🧠 **DAX (Data Analysis Expressions)** – Applied for creating dynamic measures and calculated columns
* 🏗️ **Data Modeling** – Built relationships among slicer fields and transaction tables for seamless filtering across sheets
* 📁 **File Format** – `.pbix` for Power BI project file and `.png` for dashboard snapshot previews



## 4. **Dataset Details**

The dataset consists of **UPI transaction records for the year 2024**, including key attributes such as:

* Transaction Date
* Amount & Remaining Balance
* Bank Name (Sender & Receiver)
* City, Gender, Age Group, Device Type
* Merchant Details, Payment Method, Purpose, Transaction Type
* Currency

The data is structured in tabular format and has been cleaned and transformed using Power Query within Power BI. Slicers are built on multiple categorical fields for flexible, cross-filtered exploration.


##  5. **Features / Highlights**

### 🧩 **Business Problem**

With the rapid adoption of digital payments, financial platforms need a way to monitor and interpret transaction flows, customer behavior, and usage trends.

### 🎯 **Goal of the Dashboard**

To offer a real-time, filterable analysis of UPI transactions based on multiple dimensions — enabling banks, fintechs, and analysts to draw actionable insights on user behavior and transaction dynamics.

### **Walkthrough of Key Visuals**

* 📅 **Stacked Column Chart** – Displays total transactions month-wise for 2024
* 📈📊 **Line & Column Charts (via Buttons)** – Toggleable charts show comparisons between:

  * **Transaction Amounts**
  * **Remaining Balances**
*  **Matrix Table** – Detailed view of each transaction, showing date, city, currency, amount, and balance
* **Slicers** – Interactive filters for:

  * Bank Name (Sent & Received), City, Device Type
  * Gender, Age Group, Merchant Name
  * Payment Method, Transaction Purpose & Type

### **Interactivity Across Sheets**

All slicers are synced across pages, ensuring consistent filtering across all visuals and tabs in the report.

### **Business Impact & Insights**

* Understand how transaction volumes vary by month
* Identify peak usage times and high-value customers
* Spot patterns based on gender, age, city, and device type
* Analyze the performance of specific banks, merchants, or transaction types
* Discover anomalies or imbalances using balance-related charts

