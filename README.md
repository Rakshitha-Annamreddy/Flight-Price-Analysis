# Spring Airlines Flight Price Analysis

Analyzed 10,000 flight price records to uncover pricing trends and influencing factors as part of a group project for ADTA 5130 - Data Analytics I at the University of North Texas (Spring 2024).

## 🎯 Objective
Explored how flight prices vary based on factors like destination airports, distance, airport traffic, holiday periods, and meal inclusion, delivering actionable insights for airline pricing strategies.

## 🛠️ Tools & Techniques
- **Programming**: Python (Pandas, Matplotlib)
- **Statistics**: ANOVA, Regression Analysis
- **Visualization**: Tableau, Excel
- **Dataset**: 10,000 records, 22 features (numerical, categorical, binary)

## 📊 Key Findings
- **Significant Factors**: Meal inclusion, airport traffic, and holiday periods significantly increase flight prices.
- **Non-Significant Factors**: Distance, destination airports, weekdays vs. weekends, and seasonal holidays (summer/winter) showed no strong impact on pricing.
- **Insights**: Airlines can optimize pricing by focusing on high-traffic airports and holiday demand, while customers can save by avoiding peak periods.

## 🔍 Analysis Highlights
1. **ANOVA Testing**: Found no significant price variation across destination airports (p = 0.145 > 0.05).
2. **Regression Analysis**: Confirmed no linear relationship between flight price and distance (R² = 0.005, p = 0.107).
3. **Multi-Variable Regression**: Identified airport traffic (p < 0.0001) and holiday periods (p < 0.001) as key price drivers.
4. **Meal Inclusion Impact**: Flights with meals had significantly higher prices (ANOVA, p < 0.0001).

## 📈 Visualizations
- Bar plots: Average flight prices by destination airport, day of week, and season.
- Line plot: Flight price vs. distance.

## 📂 Repository Structure
- `analysis.py`: Python script for data cleaning, statistical tests, and visualization.
- `queries.xlsx`: Excel file with raw data and pivot tables.

## 👥 Contributors
- Rakshitha Annamreddy (Me) - Data analysis, statistical testing, visualization
- Manasa Dontireddy - Project coordination, data preprocessing
- Aishwarya Shamu Guttedar - Hypothesis formulation, reporting

## 📫 Contact
- **GitHub**: [Rakshitha-Annamreddy](https://github.com/Rakshitha-Annamreddy)
- **Email**: drrakshitha@gmail.com
- **LinkedIn**: [linkedin.com/in/drrakshithaannamreddy](https://linkedin.com/in/drrakshithaannamreddy)

This project showcases my ability to analyze complex datasets, apply statistical methods, and derive business insights—skills I’m eager to bring to health data analytics roles!
