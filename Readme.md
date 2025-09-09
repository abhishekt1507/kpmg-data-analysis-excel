#  KPMG Data Analysis using Excel  

## 🎯 Objective  
The goal of this project is to analyze customer demographics, transactions, and new customer data using Microsoft Excel. The analysis aims to provide insights into business performance, customer behavior, and revenue opportunities through data cleaning, segmentation, transaction analysis, and Customer Lifetime Value (CLV) calculation.  

---

## 📑 Table of Contents  
 
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">dataset-information</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#methods">Methods</a>
- <a href="#key insights">Key Insights</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>


---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project is part of the **Data Management and Analysis with MS Excel course**.  
It involves analyzing customer and transaction datasets to:  
- Clean and prepare the data for analysis.  
- Segment customers based on demographics and wealth categories.  
- Analyze transaction patterns and brand performance.  
- Generate insights into new customers.  
- Calculate and interpret Customer Lifetime Value (CLV).  

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>
The retail industries generate large volumes of customer and transaction data.  
Without proper analysis, valuable insights into customer demographics, purchasing patterns, and long-term value may be missed.  
This project provides a structured Excel-based analysis to address these challenges.  

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2> 
The project uses the following datasets:  

- **Customer Address Data** – customer_id, address, postcode, state, country, property_valuation.  

- **Customer Demographic Data** –   customer_id, first_name, last_name, gender, past_3_years_bike_related_purchases, DOB, job_title, job_industry_category, wealth_segment, deceased_indicator, default, owns_car, tenure.

- **Transaction Data** –  transaction_id, product_id, customer_id, transaction_date, online_order, order_status, brand, product_line, product_class, product_size, list_price, standard_cost, product_first_sold_date

- **New Customer Data** –   first_name, last_name, gender, past_3_years_bike_related_purchases, DOB, job_title, job_industry_category, wealth_segment, deceased_indicator, owns_car, tenure, address, postcode, state, country, property_valuation, Rank, Value


---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>
 
- **Microsoft Excel**  
  - Data Cleaning  
  - Pivot Tables     
- **MS Power Query** (for initial transformation)  

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
kpmg-data-analysis-excel/
│
├── Task1_Data_Cleaning/
│ └── Task1_Data_Cleaning.xlsx
│
├── Task2_Customer_Segmentation/
│ └── Task2_Customer_Segmentation.xlsx
│
├── Task3_Transaction_Analysis/
│ └── Task3_Transaction_Analysis.xlsx
│
├── Task4_New_Customer_Insights/
│ └── Task4_New_Customer_Insights.xlsx
│
├── Task5_CLV_Analysis/
│ └── Task5_CLV_Analysis.xlsx
│
└── README.md
``` 

---

<h2><a class="anchor" id="methods"></a>Methods</h2>

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
     
   - CLV = (Average Purchase Value * Purchase Frequency) \ (Customer Lifespan)
     
   - Compared CLV across wealth segments, gender, and industries.  

---

<h2><a class="anchor" id="key insights"></a>Key Insights</h2>

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

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/KPMG-Data-Analysis-Excel.git


<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>
---

## 📌 Task 1: Customer Strategy

1. **High Net Worth & Affluent Customers**  
   - Provide **VIP experiences** such as priority service, early product access, and personal assistance.  
   - Retain affluent customers with **exclusive discounts**, proactive engagement (personal calls), and feedback-driven improvements.  

2. **Industry Segmentation**  
   - **Property & Finance Professionals** → Highlight premium bikes, luxury add-ons, and investment-worthy models.  
   - **IT & Entertainment Customers** → Position tech-driven bikes, smart accessories, and lifestyle-focused upgrades.  

3. **Gender-Specific Campaigns**  
   - **Men** → Promote performance bikes, adventure gear, and outdoor riding experiences.  
   - **Women** → Emphasize comfort, style, and safety features; collaborate with women bikers/influencers to build trust.  

4. **Regular (Mass) Customers**  
   - Offer bundled packages and reward programs that encourage upgrades to premium models.  

5. **Unknown Segment (Missing Data)**  
   - Collect missing demographics through surveys and purchase data.  
   - Run A/B testing with varied marketing messages to determine the most effective approach.  

---

## 📌 Task 3: Product & Sales Strategy

- **Solex (High Performer)** → Expand product range (colors, sizes, pricing tiers) and maintain strong stock levels, especially before peak seasons.  
- **Norco (Low Demand)** → Increase brand awareness through marketing campaigns, bundle Norco with popular products, and evaluate redesign opportunities.  
- **Standard Category (Revenue Leader)** → Introduce product variants, accessories, and limited-time seasonal discounts to strengthen its market share.  
- **Road Category (Growth Opportunity)** → Offer premium upgrades, performance enhancements, and limited editions for cycling enthusiasts.  
- **Mountain Category (Niche)** → Either reposition with premium adventure gear or reduce inventory to focus on stronger categories.  
- **Seasonal Promotions** → Launch campaigns ahead of peak demand months (May, August, October) and clearance sales post-dip (June, September).  
- **High-Value Customers** → Target loyal buyers (e.g., Jillie Fyndon, Glynnis Sailor) with personalized offers, early access to new launches, and loyalty rewards.  

---

## 📌 Task 4: Regional Growth Opportunities

- **New South Wales (Core Growth Hub)**  
  - Expand retail outlets in high-demand suburbs.  
  - Strengthen warehousing for faster delivery.  
  - Focus marketing efforts on peak demand months (May, August, October).  

- **Victoria (Strong Secondary Market)**  
  - Increase brand presence via pop-up stores, bike expos, and partnerships with cycling clubs.  

- **Queensland (Emerging Market)**  
  - Capitalize on year-round cycling demand.  
  - Target outdoor and adventure enthusiasts with touring and mountain bikes.  

- **Rural & Regional Expansion**  
  - Deploy mobile service vans or organize “Bike-on-Wheels” events to reach underserved areas.  

- **Cross-Sell Premium Segments**  
  - Leverage NSW and Victoria’s affluent customer base with VIP memberships, exclusive test-ride events, and early product launches.  
  

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Name:** Abhishek Tandle  
**Email:** [abhishektandle1507@gmail.com](mailto:abhishektandle1507@gmail.com)  
**LinkedIn:** [linkedin.com/in/abhishek-tandle-a10b70260](https://www.linkedin.com/in/abhishek-tandle-a10b70260)  
**GitHub:** [github.com/abhishekt1507](https://github.com/abhishekt1507)  
**Portfolio:** [abhi-shek.my.canva.site](https://abhi-shek.my.canva.site/hi-i-m-abhishek)  

---


