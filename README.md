# 🛍️ User Purchase Prediction using Logistic Regression

This project predicts whether a user will purchase a product or not based on their **Gender**, **Age**, and **Estimated Salary**.

## 📌 Objective
To build and evaluate a **binary classification model** that helps understand the purchasing behavior of users using logistic regression.

## 📊 Dataset
- **Source:** Social Network Ads (commonly used ML dataset)
- Link: https://raw.githubusercontent.com/Oscar4561/Social_Network_Ads.csv/refs/heads/main/Social_Network_Ads.csv
- **Features:**
  - Gender (encoded: Male = 1, Female = 0)
  - Age
  - Estimated Salary
- **Target:** Purchased (0 = No, 1 = Yes)

## ⚙️ Tools Used
- Python (Google Colab)
- Libraries:
  - `pandas` for data handling
  - `scikit-learn` for ML modeling
 

## ✅ Steps Covered

1. **Data Cleaning**
   - Dropped irrelevant columns (`User ID`)
   - Encoded categorical variables (Gender)
2. **Data Preparation**
   - Defined features (`X`) and label (`y`)
   - Train-test split (80/20)
3. **Model Training**
   - Logistic Regression model from `sklearn`
4. **Prediction & Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report


## 🔍 Results
- Achieved ~90% accuracy on test data
- High precision and recall for both classes
- Learned how user attributes influence purchasing behavior

## 👩‍💻 Author
Alisha Kapoor | CSE-AI @ IGDTUW  
✨ Let's connect on [LinkedIn] 
https://www.linkedin.com/in/alisha-kapoor-2ba1bb328/
