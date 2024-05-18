# Coupon_Usage_Predictive_Modeling

Our primary objective is to conduct a comprehensive comparison of seven different machine learning models to evaluate their performance in predicting whether an individual will utilize a coupon or not.

By assessing and comparing the performance of these models, we aim to gain a deeper understanding of their strengths and weaknesses, enabling us to select the most suitable model for the specific task at hand. This analysis will not only help us determine which model is the most effective but also provide insights into the factors that contribute to successful coupon utilization predictions.

### Explaining Our Models

We've developed 7 Jupyter Notebooks to identify the optimal model configurations, which you can find in the **_"\_Model Gen Notebooks"_**. In this notebook, we'll evaluate the top-performing models for Neural Network (MLPClassifier), XGBoost, Decision Tree, KNNClassifier, Logistic Regression, Support Vector Classification (SVC), and Random Forest. All of which are targeting a constructed `fbeta_score`. Each model has been fine-tuned using both GridSearch or RandomSearch for hyperparameter optimization.


### Our custom F1 Score

We built and optimized our models for using a custom F1 score with Beta = 2 (`fbeta_score`). Using this custom F2 score, we can optimize recall (failing to give a coupon to someone who would use it) while still considering the value of precision ( giving a coupon to someone who does not want it)
