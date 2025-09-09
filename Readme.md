# ✈️ KPMG Data Analysis using Excel  

## 🎯 Objective  
The goal of this project is to analyze customer demographics, transactions, and new customer data using Microsoft Excel. The analysis aims to provide insights into business performance, customer behavior, and revenue opportunities through data cleaning, segmentation, transaction analysis, and Customer Lifetime Value (CLV) calculation.  

---

## 📑 Table of Contents  
- [Overview](#overview)  
- [Problem Statement](#problem-statement)  
- [Dataset Information](#dataset-information)  
- [Tools and Technologies Used](#tools-and-technologies-used)  
- [Project Structure](#project-structure)  
- [Methods](#methods)  
- [📊 Key Insights](#-key-insights)  
  - [Task 1: Data Cleaning](#task-1-data-cleaning)  
  - [Task 2: Customer Segmentation](#task-2-customer-segmentation)  
  - [Task 3: Transaction Analysis](#task-3-transaction-analysis)  
  - [Task 4: New Customer Insights](#task-4-new-customer-insights)  
  - [Task 5: Customer Lifetime Value (CLV) Analysis](#task-5-customer-lifetime-value-clv-analysis)  
- [How to Run the Project](#how-to-run-the-project)  
- [Recommendations](#recommendations)  
- [Author & Contact](#author--contact)  

---

## 📖 Overview  
This project is part of the **Data Management and Analysis with MS Excel course**.  
It involves analyzing customer and transaction datasets to:  
- Clean and prepare the data for analysis.  
- Segment customers based on demographics and wealth categories.  
- Analyze transaction patterns and brand performance.  
- Generate insights into new customers.  
- Calculate and interpret Customer Lifetime Value (CLV).  

---

## ❓ Problem Statement  
The airline and retail industries generate large volumes of customer and transaction data.  
Without proper analysis, valuable insights into customer demographics, purchasing patterns, and long-term value may be missed.  
This project provides a structured Excel-based analysis to address these challenges.  

---

## 📂 Dataset Information  
The project uses the following datasets:  
- **Customer Address Data** – customer addresses and states.  
- **Customer Demographic Data** – demographics, gender, tenure, wealth segment, job industry.  
- **Transaction Data** – transaction dates, list prices, product categories, and total sales.  
- **New Customer Data** – demographics, address, wealth segment, job industry, and purchase behavior.  

---

## 🛠️ Tools and Technologies Used  
- **Microsoft Excel**  
  - Data Cleaning  
  - Pivot Tables  
  - Formulas & Functions  
  - Charts & Visualizations  
- **MS Power Query** (for initial transformation)  

---

## 📁 Project Structure  
KPMG-Data-Analysis-Excel/
│
├── Task1_Data_Cleaning.xlsx
├── Task2_Customer_Segmentation.xlsx
├── Task3_Transaction_Analysis.xlsx
├── Task4_New_Customer_Insights.xlsx
├── Task5_CLV_Analysis.xlsx
└── README.md


---

## ⚙️ Methods  
1. **Data Cleaning**  
   - Removed duplicates, corrected invalid entries, standardized missing data, and ensured consistent formatting.  
2. **Customer Segmentation**  
   - Grouped customers by wealth, gender, and job industry for comparative analysis.  
3. **Transaction Analysis**  
   - Identified seasonal sales trends, product performance, and customer purchasing behavior.  
4. **New Customer Analysis**  
   - Analyzed demographics, location, and property valuation of new customers.  
5. **CLV Analysis**  
   - Applied formula:  
     \[
     CLV = (Average\ Purchase\ Value \times Purchase\ Frequency) \times Customer\ Lifespan
     \]  
   - Compared CLV across wealth segments, gender, and industries.  

---

## 📊 Key Insights  

### Task 1: Data Cleaning  
- Standardized state names and gender representation.  
- Fixed anomalies in job titles and missing values.  
- Ensured transaction dates were consistent.  
- Removed incomplete transaction records.  

---

### Task 2: Customer Segmentation  
- **Mass Customers** form the majority (2000), while **Affluent Customers** are the least (979).  
- **High Net Worth Customers** are the most loyal (avg tenure 10.74 years).  
- Female customers = **2039**, slightly higher than males.  
- Males make **more purchases (50)** compared to females (48).  
- Majority work in **Manufacturing & Financial Services**, minority in **Telecommunications**.  

---

### Task 3: Transaction Analysis  
- Monthly sales spikes: **May, August, October**; dips: **June, September**.  
- **Solex** is the top-selling brand, **Norco Bicycles** the lowest.  
- **Standard category** generated the highest revenue (avg $1102).  
- Top Customer: **Jillie Fyndon ($19,071)**.  
- Average purchases per customer: **6**.  

---

### Task 4: New Customer Insights  
- Dominant industries: **Financial Services, Manufacturing, Health**.  
- **Unknown Industry** surprisingly significant.  
- **High Net Worth** → Entertainment, **Affluent** → Retail, Property, IT.  
- **Telecommunications** customers are very low.  
- Avg purchases = **50 in 3 years (~16–17 per year)** → Regular buyers.  
- **New South Wales** contributes ~50% of customers.  
- **Positive correlation** between wealth and property valuation.  
- Potential new customer revenue = **43,941,103.58**.  

---

### Task 5: Customer Lifetime Value (CLV) Analysis  
- **Mass Customers** → Highest CLV (15.23).  
- **High Net Worth** → 14.99 (lower than Mass).  
- **Affluent** → Lowest CLV (14.94).  
- **Unknown segment** → Extremely low CLV (1.31).  
- Gender CLV:  
  - Male = 15.23, Female = 14.91, Unknown = 16.35 (highest).  
- Industry CLV:  
  - Highest: **Entertainment, Health, Retail**.  
  - Lowest: **Property, Manufacturing, Agriculture, Telecom**.  

---

## ▶️ How to Run the Project?  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/KPMG-Data-Analysis-Excel.git


# 🚴 Recommendations


---

## 📌 Task 1: Customer Strategy

1. **High Net Worth & Affluent Customers**  
   - VIP perks, early access, personal assistance.  
   - Discounts, personal calls, feedback collection.  

2. **Industry Focus**  
   - Property & Finance → Premium products.  
   - IT & Entertainment → Tech gadgets, lifestyle upgrades.  

3. **Gender Preferences**  
   - Men → Performance bikes, adventure gear.  
   - Women → Style, comfort, safety; partner with influencers.  

4. **Regular Customers**  
   - Bundles, upgrades, premium rewards.  

5. **Unknowns**  
   - Collect missing data.  
   - Test different campaigns.  

---

## 📌 Task 3: Product & Sales

- **Solex** → Expand variety, ensure stock.  
- **Norco** → Boost awareness, bundles, possible redesign.  
- **Standard Category** → Add variants, accessories, seasonal offers.  
- **Road Category** → Premium upgrades, limited editions.  
- **Mountain Category** → Either invest in niche or scale down.  
- **Seasonal Campaigns** → Promotions (May, Aug, Oct); clearance (Jun, Sep).  
- **Top Customers** → Upsell with loyalty perks & exclusives.  

---

## 📌 Task 4: Regional Growth

- **NSW (Core)** → More outlets, warehousing, seasonal campaigns.  
- **Victoria (Strong)** → Pop-ups, expos, club tie-ups.  
- **Queensland (Emerging)** → Outdoor/adventure bikes.  
- **Rural** → Mobile vans, “Bike-on-Wheels” events.  
- **Cross-Sell Premium** → VIP test-rides & memberships in NSW & VIC.  

---

## 👤 Author & Contact

**Name:** Abhishek Tandle  
**Email:** [abhishektandle1507@gmail.com](mailto:abhishektandle1507@gmail.com)  
**LinkedIn:** [linkedin.com/in/abhishek-tandle-a10b70260](https://www.linkedin.com/in/abhishek-tandle-a10b70260)  
**GitHub:** [github.com/abhishekt1507](https://github.com/abhishekt1507)  
**Portfolio:** [abhi-shek.my.canva.site](https://abhi-shek.my.canva.site/hi-i-m-abhishek)  

---


