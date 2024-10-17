# **Overview**
This project analyzes COVID-19 data over 515 days, focusing on confirmed case trends, active case predictions, confirmed vs recovered case relationships, and recovery rate comparisons across states. The project uses Python libraries like pandas, matplotlib, and scikit-learn.

# Key Sections
1. **Trend Analysis of Confirmed Cases**


*   **Goal**: Visualize how confirmed cases evolved over 515 days across states.
*   **Method**: Line plots were used to identify patterns, peaks, and plateaus.
* **Outcome**: Insights on case surges and slowdowns, influenced by external factors.


2. **Predicting Future Active Cases**


*   **Goal**: Predict active cases for the next 10 days.
*   **Method**: Active cases = Confirmed - Recovered - Deceased. A linear regression model was trained on 515 days of data to predict future cases.
* **Outcome**: Generated forecasts with visual comparisons to actual data.

3. **Confirmed vs Recovered Case Relationship**
* **Goal**: Determine the correlation between confirmed and recovered cases.
* **Method**: Scatter plots and linear regression were used, with the R² coefficient measuring the relationship.
* **Outcome**: Established the strength of the correlation between confirmed and recovered cases.

4. **Comparing Recovery Rates Across States**
* **Goal**: Rank states by recovery rate.
* **Method**: Recovery Rate = (Recovered / Confirmed) × 100. Bar charts visualized the rankings.
* **Outcome: Identified top and bottom states, with factors like healthcare and population density influencing performance.
