# ML---DecisionTreeClassifier
 Titanic Survival Prediction using Decision Tree

This project focuses on predicting passenger survival on the Titanic dataset using a Decision Tree Classifier. The dataset was loaded using Seaborn and analyzed to identify key features affecting survival.

Data preprocessing included handling missing values using SimpleImputer (median for numerical features and most frequent for categorical features) and encoding categorical variables such as gender and embarkation using LabelEncoder.

Relevant features like Pclass, Sex, Fare, Embarked, and Age were selected, and the dataset was split into training and testing sets using train_test_split.

A DecisionTreeClassifier model was trained with controlled hyperparameters (max_depth=6, min_samples_split=10) to reduce overfitting and improve generalization.

Model Performance
Accuracy: ~81%
 Key Highlights
Data cleaning and preprocessing (missing value handling + encoding)
Feature selection based on domain understanding
Model training using Decision Tree Classifier
Hyperparameter tuning (pre-pruning)
Model evaluation using accuracy score
Visualization of decision tree for interpretability
