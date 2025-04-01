# Retail Analytics – Trial & Control Store Selection
## Project Overview
This project analyzes customer purchasing behavior in the Chips category for a supermarket chain. The objective is to evaluate a store trial’s impact by selecting appropriate control stores and comparing their performance with the trial store. The insights from this analysis help guide strategic decisions in the retail sector.

## Methodology and Findings

- Control Store Selection
Used Pearson correlation and magnitude distance to identify stores with sales trends similar to the trial store.A control store was chosen based on its similarity to the trial store in terms of pre-trial total sales and customer numbers. This selection was made using a weighted average of correlation and magnitude distance metrics. The visualizations of total sales and customer numbers before the trial period demonstrate that the chosen control store (Store 233) exhibits a similar trend to the trial store, providing a reliable baseline for comparison.

- Sales Trend Analysis
Compared total sales revenue, customer count, and transaction frequency between the trial and control stores.The analysis indicates that during the trial period (March-June 2019), the trial store's sales significantly outperformed the scaled control store's sales. The t-values calculated for March and April were significantly larger than the critical t-value, suggesting a statistically significant increase in sales at the trial store compared to the control.

- Customer Behavior Insights
Identified whether the sales increase was due to more purchasing customers or higher purchase frequency per customer.The analysis of customer numbers during the trial period shows that the number of customers at the trial store fell within the 95% confidence interval of the control store's scaled customer numbers. This suggests that the observed sales uplift wasn't primarily driven by an increase in customer traffic but likely by other factors like increased spending per customer, promotions, or product placements.

## Conclusion
The trial period resulted in a statistically significant increase in sales at the trial store compared to the control store. However, this increase was not accompanied by a corresponding increase in the number of customers. Further investigation is needed to understand the factors driving the sales uplift, such as changes in average transaction value, product mix, or promotional activities. The observed change in customer numbers is not statistically significant.

## Technologies Used

Python: Pandas, NumPy, Seaborn, Matplotlib

Jupyter Notebook for data analysis

Statistical Methods: Pearson correlation, hypothesis testing
