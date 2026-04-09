# Megaline Statistical Data Analysis

## Overview
This project analyzes simulated customer behavior and revenue patterns for Megaline, a telecom operator offering two prepaid plans: Surf and Ultimate. The objective is to determine which plan generates more revenue and support data-driven marketing budget decisions.

Using a sample of 500 customers, this analysis examines call, message, and internet usage throughout 2018 and compares plan performance through exploratory analysis and statistical testing.

## Business Problem
Megaline’s commercial team needs to identify which prepaid plan generates more revenue in order to allocate its advertising budget more effectively.

## Executive Summary
Ultimate generates higher and more stable revenue than Surf. Results support prioritizing Ultimate in marketing and exploring pricing and product improvements to better capture high-usage customers.

## Results Summary
- Plan with higher average revenue: Ultimate
- Main revenue driver: Ultimate generates more predictable monthly revenue, while Surf revenue is more variable and often depends on overage charges, especially for data usage
- Statistical significance: The difference in average revenue is statistically significant at a 95% confidence level, supporting Ultimate as the stronger choice by a standard data-driven business threshold
- Business recommendation: Allocate more advertising budget to Ultimate, target high-usage Surf customers for upgrades, reevaluate current plan limits and overage pricing, and consider introducing a new unlimited-tier plan to better capture heavy data users and improve long-term revenue opportunities

## Business Impact
This analysis provides a clear basis for allocating marketing resources toward higher-value plans and improving revenue predictability. It also highlights opportunities to refine pricing structures and expand product offerings to better align with customer usage patterns.

## Dataset
This project uses a simulated dataset representing 500 Megaline customers. The data is designed for analytical practice and models realistic customer activity, plan usage, and revenue behavior.

The dataset includes:
- Plan type
- City / region
- Monthly call usage
- Monthly text message usage
- Monthly internet usage
- Revenue-related data derived from plan pricing and overage charges

The analysis focuses on customer activity during 2018.

**Note:** The source dataset is not included in this repository. The notebook is presented as a portfolio artifact with saved outputs and analysis results.

## Methodology
This project includes the following steps:
1. Data cleaning and preprocessing  
2. Monthly aggregation of customer usage  
3. Exploratory data analysis of calls, messages, data consumption, and revenue  
4. Comparison of customer behavior across Surf and Ultimate plans  
5. Statistical hypothesis testing to evaluate revenue differences between plans  

## Key Insights
- Surf users more frequently exceed plan limits, leading to higher variability in revenue driven by overage charges, particularly for data usage  
- Ultimate users exhibit more consistent usage patterns and generate stable, predictable revenue through fixed plan pricing  
- Differences in usage behavior between plans directly impact revenue structure and predictability  
- High-usage Surf customers represent a clear opportunity for conversion to higher-value plans  

## Key Questions
- How do customers on Surf and Ultimate differ in their usage patterns?  
- Which prepaid plan generates more revenue on average?  
- Are the differences in revenue statistically significant?  
- What recommendation should Megaline use to guide advertising spend?  

## Conclusion
Ultimate is the stronger revenue-generating plan and should be prioritized in both marketing and pricing strategy decisions.

## Tools and Libraries
- Python  
- pandas (data manipulation)  
- numpy (numerical operations)  
- scipy (statistical testing)  
- matplotlib (data visualization)  

## Project Structure
- `SDA.ipynb` — full statistical analysis notebook  
- `README.md` — project summary and portfolio overview  

## Viewing the Project
The analysis notebook (`SDA.ipynb`) is fully executed and includes all outputs, visualizations, and conclusions. It can be viewed directly on GitHub without requiring any setup.

The source dataset is not included in this repository, as this project is presented as a portfolio artifact.

## Portfolio Notes
This project demonstrates:
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Statistical hypothesis testing  
- Business-focused analytical reasoning  
- Clear communication of findings and recommendations  
