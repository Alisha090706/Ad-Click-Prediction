🛍️ User Purchase Prediction using Machine Learning
This project focuses on predicting whether a user will purchase a product based on Gender, Age, and Estimated Salary using three popular classification models:

✅ Logistic Regression

🌳 Decision Tree

🌲 Random Forest

🎯 Objective
To build and compare classification models that predict a user’s likelihood of making a purchase, and understand which features influence the decision.

📊 Dataset
Source: Social Network Ads Dataset
Link: https://raw.githubusercontent.com/Oscar4561/Social_Network_Ads.csv/refs/heads/main/Social_Network_Ads.csv

Features:

Gender (encoded: Male = 1, Female = 0)

Age

EstimatedSalary

Target:

Purchased (0 = No, 1 = Yes)

🛠️ Tools & Libraries
Environment: Python (Google Colab)

Libraries:

pandas, numpy – data processing

matplotlib, seaborn – visualization

scikit-learn – ML modeling & evaluation

✅ Workflow Summary
Data Cleaning

Dropped User ID column

Encoded Gender (0 = Female, 1 = Male)

Data Preparation

Defined features (X) and label (y)

Train-test split (80/20)

Model Training

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Evaluation Metrics

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

📈 Model Performance
Model	Accuracy	Key Insight
Logistic Regression	88.75%	Great for linearly separable data
Decision Tree	88.75%	Captures non-linear patterns, more interpretable
Random Forest	91.25%	Best performer due to ensemble learning

🔍 Visualizations
Confusion Matrices for each model

Model-wise bar comparison of accuracy

Decision tree structure (using plot_tree)

Heatmap & classification reports

📌 Key Learnings
How categorical and numerical features affect purchase behavior

Differences between simple and ensemble classifiers

Importance of visual evaluation in ML

🚀 Future Enhancements
Hyperparameter tuning with GridSearchCV

Feature scaling and dimensionality reduction

Try models like KNN, SVM, and XGBoost

👩‍💻 Author
Alisha Kapoor
B.Tech CSE-AI @ IGDTUW
🔗 Connect on LinkedIn: https://www.linkedin.com/in/alisha-kapoor-2ba1bb328/
