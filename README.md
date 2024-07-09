
# R Language - Credit Card Risk Assessment

## Overview

This project aims to assess the risk associated with credit card applicants. The primary goal is to enable financial institutions to better evaluate and manage the risk of issuing credit cards by classifying applicants as good or bad credit risks. This classification can help in optimizing the approval process, reducing defaults, and improving overall financial stability.

## Goal

The goal of this project is to classify credit card applicants into 'good' or 'bad' credit risks based on various features in the dataset. This classification is crucial for financial institutions to make informed decisions on credit card approvals and manage risk effectively.

## Dataset

The dataset used in this project includes various features related to the applicants' personal information and financial history. The target variable 'Risk' indicates whether the applicant is a good or bad credit risk.

## Project Files

- **Final_Spotlight.pdf**: This PDF contains all the code, visualizations, and detailed analysis performed in this project.
- **Final_Spotlight.rmd**: The RMarkdown file containing the code used for data cleaning, preparation, model training, and evaluation.

## Steps and Methodology

1. **Data Preparation**: Cleaning the dataset by handling missing values, removing redundant columns, and transforming variables.
2. **Exploratory Data Analysis (EDA)**: Understanding the dataset through visualizations and summary statistics to uncover patterns and correlations.
3. **Modeling**: Applying various machine learning models to classify the credit risk:
   - K-Nearest Neighbors (KNN)
   - Random Forest
   - Boosting (XGBoost)
   - Ridge Regression
   - Lasso Regression
4. **Model Evaluation**: Evaluating the performance of the models using metrics such as ROC-AUC, confusion matrix, and variable importance plots.
5. **Conclusion**: Summarizing the findings and providing insights into the best-performing model and its implications for credit risk assessment.

## Requirements

To run this project, you will need the following R packages:

- tidyverse
- tidymodels
- xgboost
- knitr
- rmarkdown

You can install these packages using the following commands in R:

```R
install.packages("tidyverse")
install.packages("tidymodels")
install.packages("xgboost")
install.packages("knitr")
install.packages("rmarkdown")
```

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Credit_Card_Risk_Assessment.git
   cd Credit_Card_Risk_Assessment
   ```

2. Open and run the RMarkdown file using RStudio to execute the code and generate the analysis report:
   ```R
   rmarkdown::render('Final_Spotlight.rmd')
   ```

3. Alternatively, open the PDF file to review the detailed analysis and results:
   - **Final_Spotlight.pdf**

## Results

The results of the classification are presented in the form of various metrics and visualizations, highlighting the performance of different models and the importance of various features in predicting credit risk.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

If you have any questions or suggestions, feel free to reach out to me.
