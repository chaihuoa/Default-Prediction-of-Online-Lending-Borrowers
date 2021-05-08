# Default Prediction of Online Lending Borrowers Based on Machine Learning

## Introduction

Credit service has been a high-risk and high-return service for banking industry or microfinance institutions. This project uses loan data from the P2P platform Lending Club to perform machine learning and build a loan default prediction model to predict whether new loan applicants will default or not, and thus decide whether to lend or not.

This project contains four main sections: data analysis and processing, feature engineering, model training, and model evaluation. In the model training part, we mainly introduce the simple linear model Logistic Regression, vector machine LinearSVC, nearest neighbor algorithm KNeighborsClassifier, decision tree model DecisionTreeClassifier, aggregation model RandomForestClassifier and AdaBoostClassifier and XGBClassifier.

Finally, the evaluation model based on Stacking integration strategy is constructed by using XGB, random forest and support vector machine(SVM) models as primary learners and logistic regression as secondary learners.

## Model Evaluation

Introduction of commonly used classification models

- Simple linear model: LogisticRegression
- Vector machine: LinearSVC
- Nearest Neighbor Algorithm: KNeighborsClassifier
- Decision tree model: DecisionTreeClassifier
- Aggregation models: RandomForestClassifier, AdaBoostClassifier, XGBClassifier
- Stacking

## Model Scoring

- LR 0.971
- SVC 0.973
- KNC 0.989
- forest 0.991
- ABC 0.970
- XGB 0.974
- Stacking
