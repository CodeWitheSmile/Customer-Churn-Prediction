# Customer Churn Prediction

## 📌 Project Overview
This project aims to predict whether a customer will discontinue a subscription-based service. By analyzing historical customer data, we identify key factors influencing churn, allowing businesses to take proactive measures to retain customers.

## 🎯 Objective
- Predict customer churn using historical data.
- Identify key factors that contribute to churn.
- Handle missing data through appropriate imputation strategies.
- Build a model that effectively differentiates between loyal customers and those likely to churn.

## 🗂 Dataset Details
The dataset includes the following key features:
- **Demographic Information** (e.g., Gender, Age, Geography)
- **Subscription Details** (e.g., Tenure, Number of Products, Credit Score, IsActiveMember)
- **Financial Information** (e.g., Balance, Estimated Salary)
- **Churn Indicator**: Target variable (**Exited**) - whether a customer left the service (1) or remained (0).

## 🏗️ Data Preprocessing
- **Handling Missing Values**: Applied appropriate imputation strategies.
- **Encoding Categorical Data**:
  - OneHot Encoding for **Geography**
  - Label Encoding for **Gender**
- **Feature Selection**: Retained only the most relevant features (**Age, Balance, IsActiveMember**).
- **Outlier Treatment**: Identified and removed potential threats affecting model accuracy.
- **Feature Scaling**: Applied normalization where necessary.

## 🛠️ Technical Stack
- **Programming Language**: Python 🐍
- **Libraries Used**:
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `sklearn` (Scikit-learn)
  - Model Evaluation: `accuracy_score`, `confusion_matrix`

## 🚀 Model Selection & Evaluation
- **Algorithm Used**: Logistic Regression (Initially tried Linear Regression but improved to classification model)
- **Performance Metrics**:
  - Accuracy: **80.93%**
  - Precision, Recall, and F1-Score for better insights.
  - Confusion Matrix for classification performance.

## 📊 Visualization & Insights
- **Heatmaps** to understand feature correlations.
- **Distribution Plots** to analyze key factors influencing churn.
- **Training vs Testing Accuracy Comparison** to check for overfitting.

## 📌 How to Use the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/customer-churn-prediction.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script to train and evaluate the model:
   ```sh
   python train.py
   ```

## 📢 Future Enhancements
- Implement **Deep Learning Models (ANNs)** for better prediction.
- Perform **Hyperparameter Tuning** to optimize accuracy.
- Introduce **Customer Segmentation** for personalized retention strategies.

## 📜 License
This project is open-source and available under the [MIT License](LICENSE). Feel free to contribute and improve!

---

📌 **Contributors:** Your Name | GitHub: [your-profile](https://github.com/your-username)

