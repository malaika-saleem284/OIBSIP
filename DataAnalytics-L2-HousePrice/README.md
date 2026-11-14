# House Price Prediction using Linear Regression

**Oasis Infobyte Internship (OIBSIP) | Data Analytics | Level 2, Task 1**

## Objective
Build and evaluate a Linear Regression model that predicts house prices from features such as area, rooms, age, quality and location.

## Dataset
Ames Housing dataset (`train.csv`) from the Kaggle competition *House Prices - Advanced Regression Techniques*. 8 columns were selected: `GrLivArea`, `LotArea`, `BedroomAbvGr`, `FullBath`, `YearBuilt`, `OverallQual`, `Neighborhood` and the target `SalePrice`.

## Tools
Python, pandas, numpy, matplotlib, seaborn, scikit-learn, Jupyter Notebook

## Steps
1. Data loading, null check and descriptive statistics
2. SalePrice distribution (skewness)
3. Feature selection discussion
4. One-Hot Encoding of `Neighborhood`
5. Correlation heatmap
6. Train/test split (80/20)
7. Linear Regression training
8. Evaluation: MSE, RMSE, R²
9. Actual vs predicted plot and residual plot
10. Coefficient analysis
11. Bonus: Ridge and Lasso comparison

## Results
| Model | RMSE | R² |
|---|---|---|
| Linear Regression | 37,256 | 0.819 |
| Ridge | 37,214 | 0.819 |
| Lasso | 37,246 | 0.819 |

## Key Findings
- `OverallQual` and `GrLivArea` have the strongest correlation with price.
- Neighborhood has a large impact on price.
- The model under-predicts very expensive houses.

## Files
- `Malaika_Saleem_L2_Task1.ipynb`: full analysis notebook
- `train.csv`: dataset

## Links
- Demo video and LinkedIn post: https://lnkd.in/p/dpCQkVCt

## Author
Malaika Saleem | [LinkedIn](https://www.linkedin.com/in/malaika-saleem-311030428)