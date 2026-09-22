# Predicting Risk of Depression in U.S. Veterans

## Data Source:
This analysis uses publicly available data from the National Health and Nutrition Examination Survey (NHANES) between 2005-2018 (13 years). The original NHANES datasets can be accessed through the official CDC/NCHS source. 

## Sample Size:
The sample population used for analysis was 3,763 U.S. veterans (n = 3763).

## Research Questions:
- Are there biological, socioeconomic, or lifestyle factors strongly associated with depression in US veterans?
- What are some risk factors of depression for U.S. veterans?
- Which machine-learning (ML) algorithms can best predict depression in U.S. veterans?

## Methods
- Data cleaning and feature preparation in R
- Multivariate analysis
- Linear and logistic regression
- Tree-based modeling
- Train-test split and cross-validation
- Model performance evaluation

## Limitations
The findings describe associations rather than causal relationships. 
Results may be affected by self-reported measures, sample size, and the characteristics of the selected NHANES sample.

## Key Findings
Gradient Boosting (GB) had the best model performance to predict risk of depression in the sample. The AUC value was 0.85, the F-1 score was 0.40, and the sensitivity was 0.66. 
Variables related to memory, sleep, and work are strongly influential in the sample population. 
In addition, memory, sleep, work capability, and recreational activity levels were among the factors associated with depression in the selected analyzed sample.

![Main Result](results/findings-predictive-model.png)
![Main Result](results/findings-inference-oddsratios.png)


## Note
This repository is a portfolio summary of a completed academic project. The full source code and dataset are not included. 
© 2026 Maria Nguyen. Academic portfolio work. Please do not submit or represent this work as your own.
