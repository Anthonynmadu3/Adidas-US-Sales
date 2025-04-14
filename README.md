# Adidas US Sales dataset

## 1. Project Overview

### Purpose  
The dataset is primarily structured for market trend, strategic decision-making and sales performance analysis.

### Scope  
This dataset provides a full view into Adidas's sales processes in the US, suitable for analytical tasks includes, regional sales strategic, product performance tracking, retail partner evaluation, and trend forecasting.

---

## 2. Business Problem

- Missing data / inconsistencies: After review the data table discovered there are values missing in important columns like Total sales, Retailer etc. which can skew the analysis and make the conclusion inaccurate.  
- Unique Identifier: Rows like transactional ID, Sales ID there is no clear unique ID which make it difficult to differentiate between repeated or duplicate entries which may leads to problem when merging data.  
- Category Inconsistencies: Columns like retailer contains inconsistent spelling (like Foot Locker vs foot locker), this can mislead the visualizations.  
- Date granularity and format: Invoice date column may be inconsistency e.g Just date, no time for sales which will make difficult to identify weekly, daily, hourly sales trends.

---

## 3. Dataset Description

Adidas US Sales dataset holds detailed transactional data from different Adidas items sales across the United States. It contains 9,637 records and 13 features, pinch vital information such as, product type, geographic, profit, sales volume, pricing, and retailer details.  
**Source (Kaggle)**

---

## 4. Data Cleaning and Preparation

Several data wrangling steps was taken to prepare the dataset for analysis. Missing values in columns like Total Sales were identified and either replaced / removed correctly to keep data integrity. Column formats were standardized, dates were converted to appropriate date types, and numerical fields were set. Text columns like Region and Retailer were cleaned by using trimming. Duplicate entries were removed based on key identifying columns to prevent double counting.

---

## 5. Exploratory Data Analysis (EDA)

The time series chart in the center reveals clearly ascending trends in sales income from 2020 to 2021, with visible peaks in early 2021 and Q4 of both years, probably due to seasonal promotions. Geographically, West overshadows sales outcome, as displayed in the heat map and screen selections, offering powerful product presence and retail collaborations in that location. Retailer analysis unveils that foot locker, sports direct and west gear are top accomplishing channels, while Amazon and Walmart offer less proportionally. The sales method category showcases that In-store purchases remain the most primary channel, although Online and Outlet also contribute meaningfully. This complex analysis gives key insights into Adidas’ strongest regions, preferred sales methods, and top retail partners in the US market.

---

## 6. Key Insights

- Adidas accomplished steady growth in sales income between 2020 and 2021, with important rising in early 2021 and during the vacation season, showing high seasonal demand.  
- The western region appeared as number one performing location in terms of sales, proposing powerful market entry, good retail review matched to other locations.  
- Sports direct, west gear, and foot locker are the most important retail collaborations, recording for a large amount of total income, while methods like Amazon and Walmart accounting for lower sales.  
- In-store method, remains primary sales method, showing the continued significant of physical retail assessed for Adidas buyers, in despite the growing of online and outlet methods.  
- Geographically, Sales are well shared all over the states of USA, but some states particularly in the Southern and Western part of the country reveal higher demands, offering guidance for region marketing.

---

## 7. Tools & Technologies

Power Query and Excel

---

## 8. Conclusion / Recommendations

Adidas US Sales analysis shows a forceful rising trend in income between 2020 and 2021, focused mainly by in-store buys and geographically dominant in the western part of the country. Main retailers like sports direct, foot locker and west gear plays a very crucial role in Adidas market operations, while under-performing retailers like Walmart and Amazon which needs strategic analysis.  
Based on my findings, I recommended that Adidas should continue to reinforce partnerships with most performing retailers and grow its presence in high executing areas, specifically the west. Also, Increasing sales in lower-performing geographical regions and retailers through strategic promotions or locally campaigns can further enhance total performance.
