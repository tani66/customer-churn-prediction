# 📊 Customer Churn Prediction - End to End ML Project

This project predicts the likelihood of a customer leaving an e-commerce platform (Churn) using Machine Learning. It includes a complete pipeline from data preprocessing to a live interactive UI.

##  Demo
You can test the model here: [Paste your Hugging Face or Gradio Live Link here]

## 🛠️ Tech Stack
* *Language:* Python 3.x
* *Libraries:* Pandas, NumPy, Scikit-Learn, Imbalanced-learn (SMOTE)
* *Algorithm:* Random Forest Classifier (Balanced)
* *UI/Deployment:* Gradio & Hugging Face Spaces

## 📋 Project Workflow
1. *Data Loading:* Used the Indian E-commerce Customer Churn dataset.
2. *Exploratory Data Analysis (EDA):* Visualized the impact of Tenure, Warehouse Distance, and Complaints on churn.
3. *Data Balancing:* Handled class imbalance using *SMOTE* (Synthetic Minority Over-sampling Technique) to ensure the model doesn't ignore churned customers.
4. *Model Training:* Trained a Random Forest model achieving high precision and recall.
5. *Deployment:* Created an interactive dashboard using Gradio for real-time predictions.

## 📈 Key Insights
* Customers who raised *Complaints* have a significantly higher churn risk.
* *Tenure* (how long they have been a customer) is the strongest predictor of loyalty.
* High *Warehouse Distance* often correlates with customer dissatisfaction.

## 💻 How to Run Locally
1. Clone this repository.
2. Install dependencies: pip install -r requirements.txt.
3. Run the notebook or use python app.py to launch the Gradio UI.
