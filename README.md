
# Credit Card Fraud Detection
# 📋 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning models. The dataset contains transaction details and associated labels identifying whether a transaction is fraudulent or legitimate. The goal is to build a robust classification system to minimize fraud detection time and improve accuracy.
# 📊 Dataset Description
Dataset link : https://www.kaggle.com/datasets/kartik2112/fraud-detection
The dataset used in this project includes information about credit card transactions.
🔑 Key Features:

amt: Transaction amount.
lat & long: Customer's geographical location.
city_pop: Population of the city where the transaction occurred.
merch_lat & merch_long: Merchant's geographical location.
merchant: Merchant name.
category: Transaction category.
gender: Gender of the cardholder.
job: Cardholder's job.
is_fraud: Target label (1: Fraudulent, 0: Legitimate).

# ⚙️ Preprocessing:
🧹 Removed unnecessary columns like cc_num, dob, street, etc., that don't contribute to prediction.
🔄 Encoded categorical variables using Label Encoding to handle string data.

# 📐 Scaled numerical features for better model performance.
📥 Filled missing values with column-wise means.
# 🤖 Models Used
1️⃣ Logistic Regression
A simple and effective algorithm used for binary classification.
Performance Metrics:
🏆 Accuracy: 0.9955049224518147.
Confusion Matrix and Classification Report provided in the code.

2️⃣ Decision Tree Classifier
Captures non-linear relationships and interactions between variables.
Performance Metrics:
🏆 Accuracy:0.9961437345133062.
Confusion Matrix and Classification Report provided in the code.
🥇 Best Model
The Decision Tree model outperformed the Logistic Regression model in terms of accuracy and simplicity, and it was selected as the final model for deployment.

# 🔍 Explainability with SHAP
The project utilizes SHAP (SHapley Additive exPlanations) to interpret the output of the Logistic Regression model. SHAP provides insights into how each feature influences the prediction, ensuring transparency in decision-making.

📊 Summary Plot: Highlights feature importance and their impact on predictions.

# 📈 Results
✅ Decision Tree achieved the best accuracy and interpretability for detecting fraudulent transactions.
📋 SHAP analysis provided a detailed understanding of feature contributions, making the model more transparent and reliable.

# 🚀 How to Run the Project
Clone the repository and navigate to the project directory:
git clone https://github.com/Gayathri1404/Credit-Card-Fraud-Detection.git  
cd Credit-Card-Fraud-Detection

Install the required dependencies:

pip install -r requirements.txt  
Place the dataset files (fraudTest.csv and fraudTrain.csv) in the project folder.
Run the script:
python fraud_detection.py  
The best model (Decision Tree) will be saved as best_desision_tree_model.pkl.

# 🌟 Future Enhancements
Experiment with more advanced algorithms like Random Forests or XGBoost for better performance.
Implement real-time fraud detection with live transaction data.
Add a web interface for easy interaction and visualization.

# 📬 Connect with Me
Feel free to reach out if you have any questions or suggestions!

www.linkedin.com/in/gayathri-k-681b86249






