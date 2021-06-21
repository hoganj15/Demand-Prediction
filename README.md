# Demand-Prediction
Demand prediction methods used for a master's project on the topic.

The purpose of the project was to explore various demand prediction methods as per the professor's instructions given in the assignment (data splitting and loss function were specified for the students). The primary objective was to maximize the out of sample R-squared value. The analysis could be easily modified to optimize of a different loss function, however.

The data is weekly-aggregated sales for a variety of tech-related SKUs. There are three notebooks in the repository:

1. Standard Demand Prediction.ipynb
  - Utilizes standard prediction techniques like ridge regression, and optimizes on those.
2. Demand Prediction (Maximize OOS R2).ipynb
  - This notebook contains the method used to maximize out of sample R2. The techniques are not very efficient, but the dataset is small, and grading was based on how well the OOS R2 could be improved.
3. Additional Miscellaneous Methods.ipynb
  - Tests various additional methods of time series analysis. The results of each method are printed after the analysis is run.
