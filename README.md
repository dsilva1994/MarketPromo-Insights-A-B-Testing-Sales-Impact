# MarketPromo-Insights-A-B-Testing-Sales-Impact
## Project Overview
This project involves analyzing the results of a marketing experiment conducted by a fast-food company to evaluate three different promotional campaigns. The objective is to assess the effectiveness of these campaigns by analyzing sales revenue data across multiple locations over four weeks.

## Goals
The goal of this project is to:

- Compare the effectiveness of three different promotions using A/B testing.
- Provide data-driven recommendations to the marketing team on the best- sales performing promotion.


## Data
The dataset consists of sales revenue data collected from multiple locations over four weeks, and it can be accesse at [Kaggle](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test?resource=download). It includes the following columns:

- MarketID: unique identifier for market
- MarketSize: size of market area by sales
- LocationID: unique identifier for store location
- AgeOfStore: age of store in years
- Promotion: one of three promotions that were tested
- week: one of four weeks when the promotions were run
- SalesInThousands: sales amount for a specific LocationID, Promotion, and week

## Methodology
1. Exploratory Data Analysis (EDA)
The data was first examined to understand the distribution of sales across the three promotions and the variability between them.

We visualized the sales distribution, market sizes, and promotion performance.
Additional statistical checks were performed to check for potential confounding variables, such as market size and store age.

2. Statistical Testing
Three two-sample T-tests were performed to compare each pair of promotions:

- Promotion 1 vs. Promotion 2
- Promotion 1 vs. Promotion 3
- Promotion 2 vs. Promotion 3
A 99% confidence level was used, meaning an alpha level of 0.01 to reduce the risk of Type I errors.

3. Recommendations and Next Steps
- Promotion 1 and Promotion 3 are the most effective campaigns.
- Promotion 2 should be discontinued.
- A follow-up experiment comparing Promotions 1 and 3 should be conducted to select the best-performing campaign in the long term.
- The experiment could be extended beyond four weeks to capture long-term effects and account for additional variability.
- 
4. Limitations
- The experiment ran for only 4 weeks, which may not fully capture long-term trends.
- Confounding variables such as store age and market size may influence the results.

## Files
data.csv: The sales data used for analysis.
notebook.ipynb: The Jupyter Notebook with the full analysis, including EDA, statistical tests, and recommendations.
visualizations: Graphs and charts displaying key insights from the data.

## How to Run the Analysis
Prerequisites:
Make sure to install the required libraries if they are not already installed:

bash
Copiar código
pip install pandas numpy scipy seaborn matplotlib

### Steps:
Download the dataset (data.csv).
Open the Jupyter Notebook (notebook.ipynb) and run each cell to perform the analysis.
Review the results and interpretations for statistical significance and marketing insights.

## Conclusion:
- This analysis provides valuable insights into the performance of three different promotional campaigns. 
- The findings are based on rigorous statistical testing and visual data exploration, offering the marketing team data-driven recommendations on the most effective promotional strategy.

## External Sources
- [T.Test Video](https://www.youtube.com/watch?v=pTmLQvMM-1M)
- [More on Multiple comparisons problem](https://en.wikipedia.org/wiki/Multiple_comparisons_problem)
- [Confounding variables](https://www.sciencedirect.com/science/article/pii/S0085253815529748)
- [Confounding variables](https://medium.com/@jhalaksurve/understanding-confounding-variables-a-comprehensive-guide-846b30462b6b)

## How to Use This Repository
- Navigate through the folders to access code and visualizations.
- Use the Code: You can reference or adapt the Python code in the Jupyter Notebook, but do not replicate the full project.
- Licensing: This work is licensed under CC BY-NC 4.0, meaning it can be used for learning but not for commercial purposes.

## Contact Me
If you have any questions or would like to collaborate, feel free to reach out to me at:

LinkedIn: [Diana Da Silva](https://www.linkedin.com/in/diana-da-silva-01694a1a3/)

## Happy exploring! 🌟
