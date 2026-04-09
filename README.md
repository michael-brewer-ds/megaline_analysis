# Megaline Statistical Data Analysis

## Overview
This project analyzes simulated customer behavior and revenue patterns for Megaline, a telecom operator offering two prepaid plans: Surf and Ultimate. The objective is to determine which plan generates more revenue and provide a data-driven recommendation to support marketing budget allocation.

Using a sample of 500 customers, this analysis examines call, message, and internet usage throughout 2018, then compares plan performance through exploratory analysis and statistical testing.

## Business Problem
Megaline’s commercial team needs to know which prepaid plan brings in more revenue so the company can allocate its advertising budget more effectively. This project evaluates the revenue performance of Surf and Ultimate by analyzing customer usage behavior and testing whether observed differences are statistically significant.

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

## Methodology
This project includes the following steps:
1. Data cleaning and preprocessing
2. Monthly aggregation of customer usage
3. Exploratory data analysis of calls, messages, data consumption, and revenue
4. Comparison of customer behavior across Surf and Ultimate plans
5. Statistical hypothesis testing to evaluate revenue differences between plans

## Tools and Libraries
- Python
- pandas
- numpy
- scipy
- matplotlib
- seaborn

## Key Questions
- How do customers on Surf and Ultimate differ in their usage patterns?
- Which prepaid plan generates more revenue on average?
- Are the differences in revenue statistically significant?
- What recommendation should Megaline use to guide advertising spend?

## Results Summary
- Plan with higher average revenue: [Insert final result]
- Main revenue driver: [Insert final result]
- Statistical significance: [Insert final result]
- Business recommendation: [Insert final result]

## Key Insights
- Customer behavior differs across the two prepaid plans in calls, messages, and internet usage.
- Revenue is influenced not only by base plan fees, but also by how often users exceed included plan limits.
- Statistical testing is used to determine whether the revenue difference between plans is meaningful rather than random.

## Conclusion
This analysis identifies the more profitable prepaid plan and provides a data-based recommendation for how Megaline should prioritize its marketing efforts.

## Project Structure
- `SDA.ipynb` — full statistical analysis notebook
- `README.md` — project summary and portfolio overview

## How to Run
1. Open the notebook in Jupyter Notebook, JupyterLab, or VS Code.
2. Install required Python libraries if needed:
   `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`
3. Run the notebook from top to bottom to reproduce the analysis.

## Portfolio Notes
This project demonstrates:
- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical hypothesis testing
- Business-focused analytical reasoning
- Clear communication of findings and recommendations
