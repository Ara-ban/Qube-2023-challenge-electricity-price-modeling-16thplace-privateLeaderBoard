## Challenge Description

This challenge aims to model the electricity price variation using weather, energy, and commercial data for France and Germany. The objective is to explain the daily price variation of electricity futures contracts, focusing on short-term maturity contracts (24 hours). Participants are provided with training inputs (X_train), training outputs (Y_train), and test inputs (X_test).

## Solution Overview

### Understanding the Evaluation Metric

The primary focus of this solution is on understanding the evaluation metric, which is the Spearman correlation. Spearman correlation is a non-parametric measure that evaluates the strength and direction of the monotonic relationship between two variables. It is robust to outliers and does not assume a linear relationship, making it suitable for capturing complex relationships in the data.

### Exploiting the ID Column

Another critical aspect of this solution is leveraging the ID column, which likely serves as a time metric rather than just a unique identifier. By recognizing the ID column's potential role as a time series indicator, the model can better account for temporal dependencies and trends in the data. This approach enhances the model's ability to provide accurate and reliable estimations by utilizing the sequential nature of the ID column.

