# GLOBAL_STARTUP_INVESTMENT_DASHBOARD

#  Power BI Dashboard: Startup Investment Analysis

## Problem Statement
 The goal is to help users uncover patterns in global investment, identify high-growth sectors, and understand where the startup momentum lies.


## Dataset Description

The dataset includes the following columns for each startup:

- **Startup Name** – Name of the startup  
- **Industry** – The sector the startup belongs to (e.g., AI, Fintech, HealthTech)  
- **Funding Rounds** – Number of funding rounds raised  
- **Investment Amount (USD)** – Total investment amount received  
- **Valuation (USD)** – Estimated company valuation  
- **Number of Investors** – Total number of investors backing the startup  
- **Country** – Country where the startup is based  
- **Year Founded** – Year of founding  
- **Growth Rate (%)** – Annual growth rate of the startup  


###  DAX Measures Created

- **Total Investment**  
  Calculates the total funding raised across all startups.

- **Total Startup Count**  
  Counts the total number of startups in the dataset.

- **Average Valuation**  
  Calculates the mean company valuation, used to compare across years or countries.

- **Average Growth Rate**  
  Calculates the mean of all startup growth rates.

- **Sum of Growth Rate**  
  Computes total growth rate contribution of startups within a region or category, used in scatter visualizations.



### Calculated Columns Added

- **Mega Investment Category**  
  Classifies each startup as “Yes” or “No” based on whether their investment exceeded a certain threshold (e.g., $500M). Useful for filters and visuals.

- **Valuation Range**  
  Groups startups into valuation buckets (e.g., "< $100M", "$100M–$500M", "$500M–$1B", "$1B+"). Helps create clearer filters and comparative visuals.


##  Visualizations and Insights

###  KPI Cards
- **Total Investment**  
- **Total Startup Count**  
→ Provide a quick summary of overall market activity and dataset scale.

###  Stacked Bar Chart
- **Total Investment by Industry**  
→ Highlights which industries attract the most venture capital and helps compare investment size between them.

### Map Visual
- **Startup Count by Country**  
→ Presents geographical startup distribution, showcasing countries with the most startup activity.

###  Tree Map
- **Startup Count by Industry**  
→ Visually emphasizes industry-wise startup presence in terms of count, helping to spot dominant sectors.

###  Line Chart
- **Average Valuation by Year Founded**  
→ Tracks valuation trends over time, revealing boom or decline phases in startup economics.

###  Donut Chart
- **Startup Count by Funding Rounds**  
→ Illustrates how many startups fall into different levels of fundraising activity.

###  Scatter Plot
- **Average Valuation and Sum of Growth Rate by Country**  
→ Combines valuation and growth dimensions to highlight which countries are fostering both high-value and high-growth startups.


###  Slicer Panel (Interactive Filtering)
- **Country**
- **Industry**
→ Enables users to slice the dataset dynamically, filter across visuals, and focus on specific regions, or investment levels.


##  Conclusion

This Power BI dashboard transforms startup data into actionable intelligence. It reveals:

 1. Top-performing industries and countries in terms of funding and startup count  
 2. Valuation and growth patterns over the years  
 3. Countries with the most high-growth and high-value startups  
 4. Distribution of mega-funded startups  

It is designed to support strategic investment decisions, market research, and innovation tracking.





