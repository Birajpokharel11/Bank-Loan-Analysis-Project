 # 🎯 **Bank Loan Analysis Project**

## 📝 **Overview**
This project is a comprehensive data analysis focused on understanding and optimizing the loan portfolio of a financial institution. By analyzing key metrics and visualizing data using **MS SQL Server** and **Power BI**, this project aims to provide actionable insights that can help improve decision-making, risk management, and overall portfolio performance.

## 🎯 **Project Objectives**
The primary goals of this project are:

- 🔍 **Data Extraction and Analysis**: Retrieve and analyze critical loan data to understand trends and metrics such as total loan applications, funded amounts, repayments, interest rates, and borrower profiles.
- 📊 **KPI Monitoring**: Develop key performance indicators (KPIs) to track the performance of loans, borrower behavior, and financial health.
- 📈 **Data Visualization**: Use Power BI to create interactive dashboards that allow stakeholders to easily interpret data and make informed decisions.
- 💡 **Insight Generation**: Provide actionable insights based on data analysis to optimize loan management, reduce financial risk, and improve customer satisfaction.

## 🛠️ **Tools & Technologies Used**
- 🗄️ **MS SQL Server**: Database management, data storage, and execution of SQL queries to extract and analyze loan-related data.
- 📊 **Power BI**: Creating visualizations and interactive dashboards to present the analyzed data in a clear and user-friendly manner.
- 📑 **Excel**: Preliminary data cleaning, exploration, and generating pivot tables and charts for quick insights.

## 📂 **Dataset Overview**
- 🆔 **ID**: Unique identifier for each loan application.
- 🌍 **Address State**: The state where the borrower resides.
- 📝 **Application Type**: The type of application (e.g., INDIVIDUAL).
- 💼 **Employment Length**: The number of years the borrower has been employed.
- 🏢 **Employer Title**: The name of the borrower’s employer.
- 🎓 **Grade**: The loan grade assigned based on risk.
- 🏠 **Home Ownership**: The ownership status of the borrower's home (e.g., RENT, MORTGAGE).
- 📅 **Issue Date**: The date when the loan was issued.
- 📈 **Last Credit Pull Date**: The most recent date when the borrower's credit was checked.
- 💳 **Last Payment Date**: The date of the last payment made by the borrower.
- ✅ **Loan Status**: The current status of the loan (e.g., Fully Paid, Charged Off).
- 📅 **Next Payment Date**: The date of the next scheduled payment (if applicable).
- 🆔 **Member ID**: A unique identifier for the borrower.
- 🎯 **Purpose**: The purpose of the loan (e.g., car).
- 📊 **Sub-Grade**: A more specific grade within the main grade category.
- 🕒 **Term**: The loan term in months (e.g., 36 months, 60 months).
- ✔️ **Verification Status**: The status of income verification (e.g., Verified, Source Verified, Not Verified).
- 💰 **Annual Income**: The annual income of the borrower.
- ⚖️ **DTI (Debt-to-Income Ratio)**: A ratio that compares the borrower's debt to their income.
- 💵 **Installment**: The fixed monthly payment amount.
- 💸 **Interest Rate**: The interest rate applied to the loan.
- 🏦 **Loan Amount**: The total amount of the loan.
- 🔢 **Total Accounts**: The total number of credit accounts held by the borrower.
- 💲 **Total Payment**: The total amount paid by the borrower over the life of the loan.

## 📈 **Key Performance Indicators (KPIs)**
The project focuses on several key KPIs that are crucial for understanding the performance and risk associated with the loan portfolio:

- 📅 **Total Loan Applications**: The total number of loan applications received, analyzed with Month-to-Date (MTD) and Month-over-Month (MoM) tracking to observe trends over time.
- 💵 **Total Funded Amount**: The total amount disbursed as loans. This KPI is critical for understanding the scale of lending operations, with MTD and MoM comparisons to identify fluctuations.
- 💰 **Total Amount Received**: The total repayments made by borrowers. This KPI helps in assessing the cash flow and financial health of the loan portfolio.
- 📉 **Average Interest Rate**: The average interest rate applied across all loans, monitored for Month-over-Month variations to understand changes in lending costs.
- 📊 **Average Debt-to-Income Ratio (DTI)**: This KPI measures the financial health of borrowers by comparing their debt obligations to their income, with a focus on MoM changes.

## 📊 **Dashboards**

### 1. **Summary Dashboard**
**Purpose**: To provide a high-level overview of key loan metrics and performance indicators.

**Features**:
- 📊 Visual representation of **Total Loan Applications**, **Total Funded Amount**, and **Total Amount Received**.
- ⚖️ Breakdown of **Good Loans vs. Bad Loans**, including application percentages and funded amounts.
- 🗂️ A **Loan Status Grid View** that categorizes loans based on their status, helping stakeholders quickly assess portfolio health.

### 2. **Overview Dashboard**
**Purpose**: To drill down into specific aspects of the loan data, such as trends over time, regional distribution, and borrower demographics.

**Features**:
- 📈 **Monthly Trends (Line Chart)**: Analyzes the number of loans issued and the total amount funded over time, helping identify seasonal patterns or shifts in lending activity.
- 🌍 **Regional Analysis (Filled Map)**: Displays loan distribution by state or region, highlighting areas with high or low lending activity.
- 🧁 **Loan Term Analysis (Donut Chart)**: Shows the distribution of loan terms (e.g., 12 months, 24 months) to understand borrower preferences.
- 📊 **Employee Length Analysis (Bar Chart)**: Examines the correlation between borrower employment length and loan approval rates.
- 🏠 **Home Ownership Analysis (Tree Map)**: Provides insights into how home ownership status affects loan application and approval rates.

### 3. **Details Dashboard**
**Purpose**: To offer a comprehensive and detailed view of all loan-related data, allowing users to explore specific metrics and borrower profiles.

**Features**:
- 📊 Consolidated view of all key metrics, including **total applications**, **funded amounts**, **repayments**, **interest rates**, and **DTI ratios**.
- 🔍 **Interactive grid and filter options** to drill down into specific data points, borrower details, or loan statuses.
- 🖥️ A **user-friendly interface** that facilitates quick access to critical information for deeper analysis.

## 🛠️ **Project Workflow**

### **1. Data Extraction:**
- 🗄️ Connected to the SQL Server database and executed SQL queries to extract relevant loan data.
- 🧹 Performed data cleaning and preprocessing to ensure the data was accurate and ready for analysis.

### **2. Data Analysis:**
- 🔍 Analyzed the extracted data using SQL queries to calculate KPIs and identify trends and patterns.
- 📊 Segmented the data based on various criteria such as loan status, borrower demographics, and loan terms.

### **3. Data Visualization:**
- 📈 Imported the analyzed data into Power BI for visualization.
- 🎨 Created interactive dashboards that visualize the KPIs and provide clear, actionable insights into the loan portfolio.

### **4. Insight Generation:**
- 💡 Interpreted the visualized data to generate insights that can help in decision-making.
- 📝 Provided recommendations for optimizing loan management, reducing financial risk, and improving customer service.

## 💡 **Insights & Recommendations**
- 🎯 **Optimizing Loan Applications**: By analyzing the trends in loan applications and funded amounts, the bank can optimize its marketing and loan approval strategies to target high-potential customer segments.
- 🔍 **Risk Management**: Monitoring the **Average DTI** and **Interest Rates** helps in assessing the risk profile of borrowers and adjusting lending policies accordingly.
- 🌍 **Regional Strategies**: The regional analysis can guide the bank in tailoring its loan products and services to the needs of different geographical areas.

