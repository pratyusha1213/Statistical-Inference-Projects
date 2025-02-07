# A/B Testing Projects: Fast Food Marketing Campaign & Mobile Games

This repository contains two distinct projects that utilize A/B testing to make data-driven decisions in different domains: fast-food marketing and mobile gaming.

---

## 1. Fast Food Marketing Campaign A/B Test

Looker Studio Dashboard: https://lookerstudio.google.com/reporting/fd310c6b-0830-461f-8620-007cc9fb8584/page/LoVYE

### Scenario

A fast-food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are recorded for the first four weeks.

### Objective
To determine which of the three marketing campaigns has the greatest positive effect on weekly sales of a new menu item.

### Methodology
- Randomly selected markets were assigned one of three promotional campaigns.
- Weekly sales data was collected over a 4-week period.
- Statistical analysis was conducted to compare the performance of the campaigns.

### Key Steps
1. Exploratory data analysis (EDA) to understand sales trends across campaigns.
2. Hypothesis testing to identify statistically significant differences in sales performance.
3. Visualization of results to aid decision-making.

### Conclusion
The statistical analysis shows that promotions 1 and 3 consistently produce higher average revenues compared to promotion 2 across all market sizes. Therefore, the organization might consider incorporating promotions 1 and 3 into its upcoming marketing strategies.

---

## 2. A/B Testing in Mobile Games

### Scenario
## Scenario

The dataset consists of A/B test results for a mobile game called Cookie Cats, which was used to study the impact of changing a game feature on player engagement. Specifically, the test involved moving the first gate in the game from level 30 to level 40 to evaluate if this change would influence player behavior. Players who installed the game during the testing period were randomly assigned to one of two groups: the control group (gate_30), where the gate was at level 30, and the experimental group (gate_40), where the gate was moved to level 40.

### Objective
To evaluate whether moving the first gate in the game from level 30 to level 40 affects player engagement.

### Methodology
- Players were randomly assigned to two groups: 
  - **Control Group (gate_30):** Gate at level 30.
  - **Experimental Group (gate_40):** Gate at level 40.
- Metrics such as player retention and progression were compared between groups.
- Statistical testing was applied to assess the impact of the change.

### Key Steps
1. Data preprocessing to clean and prepare test results.
2. EDA to observe player engagement metrics.
3. A/B testing to quantify the effects of the gate level change.
4. Presentation of insights through graphs and summary statistics.

### Conclusion
Based on the analysis of retention rates, hypothesis testing, and bootstrap confidence intervals, it is evident that Gate 30 significantly outperforms Gate 40 in terms of 7-day retention rates. The p-value from hypothesis testing is less than 0.05, and the confidence intervals for the difference in proportions do not include zero, further supporting this conclusion.

To maximize player retention, it is recommended to continue using Gate 30 as the gating strategy. Moving to Gate 40 could negatively impact the retention rates and overall user engagement.

---

## Tools & Technologies
- **Python**: Data analysis and visualization.
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, SciPy, and others.
- **Statistical Techniques**: Hypothesis testing, confidence intervals, and t-tests.

## How to Use
1. Clone this repository.
2. Open the respective Jupyter Notebooks to explore the analyses:
   - `Fast Food Marketing Campaign AB Test.ipynb`
   - `AB TESTING IN MOBILE GAMES.ipynb`
3. Run the notebooks cell-by-cell to reproduce the analyses.

## Results
- **Fast Food Campaign**: Insights into the most effective promotional strategy.
- **Mobile Games**: Understanding the impact of a game design change on player behavior.

---

## License
This repository is licensed under the MIT License. Feel free to use and adapt the code for your projects.
