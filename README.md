# Python_EDA_CampaignPerformanceAnalysis

**Exploratory Data Analysis Project of Google Ads Campaign Sales**

This project analyzes a year-long advertising performance dataset from Google Ads, specifically focusing on promotional campaigns for a Data Analysis course. The dataset includes various ad metrics such as impressions, clicks, cost, conversion rate, and sales amount. With various intentional quality issues such as format and spelling inconsistencies, missing values, and duplicates, the dataset reflects real-world challenges that marketers commonly face when preparing for data analysis.

Collected from Kaggle - Google Ads Sales Dataset, the dataset consists of 2,600 entries and 13 features (5 numerical, 8 categorical). Analyzing this type of campaign allows marketers to uncover patterns in consumer behavior and optimize ad performance based on factual data.

**Data Cleaning**

Before analysis, several data quality issues were identified and resolved:
1. Symbols removement in _Cost_ and _Sales_Amount_ to allow numerical processing.
2. Date format standardization into MM/DD/YYYY in _Ad_Date_.
3. Typo handling and capitalization in string columns such as _Campaign_Name_, _Location_, _Device_, and _Keyword_.
4. Missing values handling on 7 columns.
5. Duplicate removal to ensure accurate analysis.

**Analysis Goals**
1. Identify days of the week with the highest return on ad spend.
2. Explore how ad cost and clicks vary across different devices.
3. Evaluate performance of keywords based on impressions and cost.

**Insights**
1. Ad costs stay relatively stable during the week, but sales peak on Thursdays and Fridays, suggesting stronger consumer engagement.
3. Ads on mobile devices incur slightly higher costs, but clicks are evenly distributed across all device types.
4. Certain keywords, such as “Analytics for data”, “Data analytics course”, and “Data analytics training” show high impressions at low cost per impression, making them efficient for higher reach.

**Recommendations**
1. Prioritize ad placement on Thursdays and Fridays to leverage cost return.
2. Maintain broad device targeting, but consider slightly higher budget for mobile users.
3. Consider combining discount strategies with cost-efficient keywords to boost reach and optimize spending.

If you have feedback, questions, or suggestions, feel free to reach me out!

Email: rafalinafania@gmail.com

LinkedIn: linkedin.com/in/fania-rafalina-fadli

GitHub: rafalinafd
