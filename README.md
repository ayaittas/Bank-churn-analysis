# Why do bank customers leave?

Group project for the course RM402E Statistics & Data Analysis at Rennes School of Business (2026).

## About the project

We study the churn of 10,000 customers of a European retail bank present in France, Germany and Spain. We describe the customers who leave, we test if the differences with the customers who stay are statistically significant, and we build models to predict which customers are likely to leave.

## Files

| File | Content |
|---|---|
| `Bank_Churn_Group_Project.ipynb` | notebook with the code, the results and our comments |
| `Churn_Modelling.csv` | dataset (10,000 customers, 14 columns) |

The dataset is the [Churn Modelling dataset from Kaggle](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling).

## Methods

- Data cleaning and descriptive statistics
- Exploratory data analysis
- Probabilities, normality tests and Central Limit Theorem
- Confidence intervals for a mean and for a proportion
- Hypothesis tests (Mann-Whitney, chi-square, Kruskal-Wallis, Spearman correlation)
- Logistic regression and random forest

## Main results

- 20.37% of the customers left the bank.
- Age is the main factor. 44.65% of the customers older than 50 left.
- The churn rate in Germany (32.4%) is twice the rate in France (16.2%) and Spain (16.7%).
- Inactive members, women and customers with 3 or 4 products leave more often.
- Salary, tenure and credit card are not linked to churn.
- The random forest reaches an accuracy of 86% on the test set and finds 46% of the leavers.

## How to run the notebook

1. Open `Bank_Churn_Group_Project.ipynb` in Google Colab.
2. Put `Churn_Modelling.csv` in the same folder. In Colab, upload it in the Files panel or use the two commented lines of the second code cell.
3. Run all the cells.


## Team members

- Aya ITTAS
- Mohamed Amine DOUAH
- Givi KVARATSKHELIYA
- Eva BAGAEVA
- Yashwanth Chamanahalli NAGESH
- Darryl Krystale MEHOHI
