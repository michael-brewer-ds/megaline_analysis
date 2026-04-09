# Megaline Statistical Data Analysis

## Overview
This project analyzes simulated customer behavior and revenue patterns for Megaline, a telecom operator offering two prepaid plans: Surf and Ultimate. The objective is to determine which plan generates more revenue and provide a data-driven recommendation to support marketing budget allocation.

Using a sample of approximately 500 customers, this analysis examines call, message, and internet usage throughout 2018, then compares plan performance through exploratory analysis and statistical testing.

## Business Problem
Megaline’s commercial team needs to know which prepaid plan brings in more revenue so the company can allocate its advertising budget more effectively. This project evaluates the revenue performance of Surf and Ultimate by analyzing customer usage behavior and testing whether observed differences are statistically significant.

## Executive Summary
Ultimate generates higher and more stable revenue than Surf, with statistically significant results. The analysis supports prioritizing Ultimate in marketing, optimizing pricing structures, and exploring a new unlimited-tier plan to better capture high-usage customers.

## Results Summary
- Plan with higher average revenue: Ultimate
- Main revenue driver: Ultimate generates more predictable monthly revenue, while Surf revenue is more variable and often depends on overage charges, especially for data usage
- Statistical significance: Yes. The difference in average revenue is statistically significant at a 95% confidence level, supporting Ultimate as the stronger choice by a standard data-driven business threshold
- Business recommendation: Allocate more advertising budget to Ultimate, target high-usage Surf customers for upgrades, reevaluate current plan limits and overage pricing, and consider introducing a new unlimited-tier plan to better capture heavy data users and improve long-term revenue opportunities

## Business Impact
This analysis informs marketing budget allocation and highlights opportunities to improve pricing strategy and product design. Recommendations include shifting focus toward higher-value customers, refining plan structures, and expanding offerings to increase revenue stability.

## Dataset
This project uses a simulated dataset representing approximately 500 Megaline customers. The data is designed for analytical practice and models realistic customer activity, plan usage, and revenue behavior.

The dataset includes:
- Plan type
- City / region
- Monthly call usage
- Monthly text message usage
- Monthly internet usage
- Revenue-related data derived from plan pricing and overage charges

The analysis focuses on customer activity during 2018.

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
Ultimate is the stronger revenue-generating plan and the better candidate for increased advertising investment. The analysis also reveals opportunities to improve pricing strategy through plan adjustments and the potential introduction of an unlimited-tier offering for high-usage customers.

## Tools and Libraries
- Python  
- pandas (data manipulation)  
- numpy (numerical operations)  
- scipy (statistical testing)  
- matplotlib (data visualization)  

## Project Structure
- `SDA.ipynb` — full statistical analysis notebook  
- `README.md` — project summary and portfolio overview  

## How to Run
1. Open the notebook in Jupyter Notebook, JupyterLab, or VS Code  
2. Install required Python libraries if needed:  
   `pandas`, `numpy`, `scipy`, `matplotlib`  
3. Run the notebook from top to bottom to reproduce the analysis  

## Portfolio Notes
This project demonstrates:
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Statistical hypothesis testing  
- Business-focused analytical reasoning  
- Clear communication of findings and recommendations
