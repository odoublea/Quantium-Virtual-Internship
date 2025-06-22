# Quantium Virtual Internship

This repository contains my solution for the Quantium Data Analytics Virtual Experience Internship Program on Forage,
demonstrating practical data analysis skills through a real-world retail problem.

## Introdution

Founded in 2002, Quantium is a global leader in Data Science and Artificial Intelligence. They harness the power of
data to drive revolutionary change that benefits us all and deliver the best results for our clients.
They are committed to growing a team of ambitious, diverse, and fun people!

As part of their virtual internship, I engaged with the challenging yet rewarding work of their analytics team, whose
core responsibility is to provide actionable data insights for strategic business decision-making. This internship
provided hands-on experience in crucial data analysis phases, including data validation, cleaning, visualization,
statistical testing, and the art of presenting findings and recommendations.

## Project Overview: Chips Category Deep Dive

As a member of Quantium’s retail analytics team, I was tasked by a client – the Category Manager for Chips – to gain a
deeper understanding of customer purchasing behavior within the chips category and identify key customer segments. The
insights derived from this analysis are intended to inform the supermarket's strategic plan for the chips category over
the next six months.

## Data Analytics Technical Skills

- Problem Definition & Scoping
- Advanced Data Cleaning & Validation: Handling inconsistencies, missing data, and outliers.
- Exploratory Data Analysis (EDA): Identifying trends, patterns, and drivers.
- Data Visualization: Crafting compelling charts and graphs for clear communication.
- Statistical Testing & Hypothesis Testing: Deriving statistically sound conclusions (e.g., t-tests, chi-squared tests, if performed).
- Data Storytelling & Presentation: Translating complex data into actionable business recommendations.

## Resources

### Software

- Microsoft Excel
- VS Code

### Programming Language

- Python

### Key Libraries

- Pandas: For robust data manipulation and analysis.
- Matplotlib & Seaborn: For static and exploratory data visualizations.
- Plotly: For interactive data visualizations

## Task One: Data preparation and customer analytics

### Task One Objectives

1. Analyze transaction and customer data to identify trends and inconsistencies
    - Retail Analytics
    - Understand the types of customers who purchase Chips and,
    - Their purchasing behaviour within the region.
2. Develop Metrics and examine data drivers to gain insights into overall data performance
3. Create visualization and prepare findings to formulate a clear recommendation for the clien's strategy

### Methodology

- Examined transaction and customer datasets. This involved addressing inconsistencies, handling missing values, identifying
and managing outliers, correctly categorizing items, and ensuring numeric data integrity across all tables.
- Data Integration: Performed checks for similar issues in customer data (e.g., null values) and then merged customer data
with transactional data to create a unified dataset ready for analysis.
- Metric Definition: Defined critical metrics to guide the analysis, including total sales, primary sales drivers, demographic sales hotspots,
and percentage representation of various customer segments
- Exploratory Data Analysis (EDA): Conducted in-depth data exploration, creating informative charts and graphs to highlight interesting trends,
patterns, and initial insights.

### Key Insight

- Targeting Strategy: Identified *Mainstream Young Singles and Couples* for optimal targeting, considering both population size and average spending habits on chips.
- Brand & Packet Size Preference: Determined a significant preference for Tyrrells chips, with customers being 23% more likely to purchase it.
Additionally, a specific packet size of 270g was identified as highly popular.

### Recommendation

Based on the insights gained from the analysis of transaction and customer data, the following strategic recommendations are proposed for the Category Manager for Chips:

- Optimize Product Assortment and Placement:
  - Focus on Tyrrells 270g: Given the 23% higher likelihood of purchase, strategically prioritize stock levels and prominent shelf placement
for this specific brand and packet size. This product is a clear sales driver.

  - Review Underperforming SKUs: Analyze sales data for other brands and packet sizes. Consider reducing inventory or discontinuing products
that show consistently low sales volume or profitability to free up shelf space for high-demand items.

- Targeted Marketing Campaigns:

  - Leverage High-Value Segments: Develop marketing campaigns specifically tailored to "Older Families" and "Young Families". While "Older Families" are topping the charts,
  the "Young Families" representing 12.7% of the customer population and 16.4% of total sales presents a unique opportunity. For future growth, a Campaigns should focus
  on their purchasing habits and motivations, potentially through personalized offers or loyalty programs.
  - Promote Tyrrells and 270g size: Feature the preferred brand and packet size heavily in promotions, in-store displays, and digital advertisements to capitalize on existing customer preference.

- Strategic Pricing and Promotions:
  - Bundling Opportunities: Explore bundling the popular 270g chips with complementary products (e.g., dips, drinks) popular with the identified target segments to increase average transaction value.
- Continuous Monitoring and Adaptation:
  - Regular Review Meetings: Schedule regular meetings with the Category Manager to review performance metrics and adapt the strategic plan based on new data and market shifts.

## Task Two: Experimentation and uplift testing

### Task Two Objectives

1. Examine the performance in trial vs control stores to provide a recommendation for each location based on our insight.

### Process
