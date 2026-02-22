# Machine-Learning-Model
Development of a model that chooses the correct mobile phone plan, analyzing customer behavior.

## Skills demonstrated
- Machine Learning
- Learning algorithms
- Scikit-Learn library and metrics
- Exploratory Data Analysis
- Training, validation, and test datasets
- Hyperparameters
- Dummy Model
- Logistic Regression
- Decision Tree
- Random Forest
- Accuracy Score

## Tools
Python, pandas, sklearn, accuracy_score, train_test_split

## Results
Based on hyperparameter fitting on the validation dataset, the Random Forest model with n_estimators = 80 is selected as the best-performing model.

Decision Tree provides a simpler and interpretable alternative, while Logistic Regression offers insights into the relative effect of features but with slightly lower accuracy.

All models exceed the baseline established by DummyClassifier (0.694), confirming that they effectively learn from user behavior to predict the optimal mobile plan.

## Notebook
See model_development.ipynb
