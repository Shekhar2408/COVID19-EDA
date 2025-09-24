🦠 COVID-19 Exploratory Data Analysis (EDA)
This project performs a comprehensive Exploratory Data Analysis (EDA) on COVID-19 datasets to uncover patterns, trends, and insights about the pandemic.
Using Python, Pandas, Matplotlib, Seaborn, and Plotly, this notebook explores worldwide COVID-19 data at both country and continent levels.

🎯 Objectives
- Data cleaning and preprocessing.
- Explore Total Cases, Recoveries, and Deaths across countries.
- Visualize testing efforts vs cases detected.
- Compare cases and deaths per continent.
- Analyze trends over time (daily/weekly growth).
- Perform country-specific analysis (e.g., USA).

🛠️ Tools & Libraries
- Python 3, Jupyter Notebook
- Libraries:
- pandas → Data wrangling
- numpy → Numerical operations
- matplotlib, seaborn → Static visualizations
- plotly → Interactive charts

📊 Dataset Information
- covid.csv → Raw COVID-19 statistics by country (cases, tests, deaths).
- covid_grouped.csv → Aggregated dataset grouped by country and date.
- coviddeath.csv → Dataset containing death details.

📈 Key Insights
- Top 15 countries with the highest number of cases and tests visualized with bar charts.
- Continent-wise spread shows unequal testing and case detection.
- Scatter plots reveal strong correlation between total cases and total deaths.
- Testing per million highlights disparities across countries.
- Log-scale visualizations uncover hidden patterns in countries with fewer cases.
- Time-series plots show how confirmed cases and deaths rose globally.
- USA-specific analysis reveals exponential growth in confirmed cases.

📸 Sample Visualizations
- Bar chart → Top 15 countries by Total Cases.
- Horizontal bar chart → Total Tests per Country.
- Scatter plot → Total Cases vs Total Deaths (with log scale).
- Line/bar charts → Daily Confirmed Cases & Deaths (time-series).
- Continent-level scatter → Spread of COVID-19 by region.

