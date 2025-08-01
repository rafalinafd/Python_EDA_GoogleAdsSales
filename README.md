# Python_EDA_CampaignPerformanceAnalysis
Exploratory Data Analysis Project of Google Ads Campaign Sales

This project analyzes a year-long advertising performance dataset from Google Ads, specifically focusing on promotional campaigns for a Data Analysis course. The dataset includes various ad metrics such as impressions, clicks, cost, conversion rate, and sales amount. With various intentional quality issues such as format and spelling inconsistencies, missing values, and duplicates, the dataset reflects real-world challenges that marketers commonly face when preparing for data analysis.

Collected from Kaggle - Google Ads Sales Dataset, the dataset consists of 2,600 entries and 13 features (5 numerical, 8 categorical). Analyzing this type of campaign allows marketers to uncover patterns in consumer behavior and optimize ad performance based on factual data.

**Data Cleaning**
Before analysis, several data quality issues were identified and resolved.
1. Currency Symbol Removal:
Symbols in Cost and Sales_Amount were removed to allow numerical processing.
2. Date Format Standardization:
Dates in Ad_Date had inconsistent formats (slashes, dashes, different day/month orders). All were standardized to MM/DD/YYYY.
3. Typo Handling in String Columns:
Standardized _Campaign_Name_ and _Location_ to fix inconsistent spellings.
Capitalized _Device_ values to address casing variations.
Corrected typos in _Keyword_ entries for better consistency.
4. Missing Values Handling:
7 numerical columns had missing values.
5. Duplicate Removal:
One duplicate _Ad_ID_ was found and removed to ensure accurate analysis.

**Analysis Goals**
1. Identify days of the week with the highest return on ad spend.
2. Explore how ad cost and clicks vary across different devices.
3. Evaluate performance of keywords based on impressions and cost.

**Insights**
1. Ad Scheduling:
Ad costs stay relatively stable during the week, but sales peak on Thursdays and Fridays, suggesting stronger consumer engagement.
3. Device Targeting:
Ads on mobile devices incur slightly higher costs, but clicks are evenly distributed across all device types.
4. Keyword Performance:
Certain keywords, such as “Analytics for data”, “Data analytics course”, and “Data analytics training” show high impressions at low cost per impression, making them efficient for higher reach.

**Recommendations**
1. Prioritize ad placement on Thursdays and Fridays to leverage cost return.
2. Maintain broad device targeting, but consider slightly higher budget for mobile users.
3. Consider combining discount strategies with cost-efficient keywords to boost reach and optimize spending.

If you have feedback, questions, or suggestions, feel free to reach me out!
Email: rafalinafania@gmail.com
LinkedIn: linkedin.com/in/fania-rafalina-fadli
GitHub: rafalinafd
