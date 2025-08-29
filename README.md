# Loan Approval Prediction using Machine Learning  

## 📌 Project Overview  
This project focuses on predicting **loan approval status** based on applicant financial information using machine learning.  
The goal is to build a reliable classification model that helps financial institutions make informed lending decisions.  

## 📂 Dataset  
The dataset was obtained from **Kaggle** and includes applicant details with the following features:  

- **income_annum** – Annual income of the applicant  
- **loan_amount** – Loan amount applied for  
- **loan_term** – Loan repayment term (in months)  
- **cibil_score** – Applicant’s CIBIL (credit) score  
- **residential_assets_value** – Value of residential property  
- **commercial_assets_value** – Value of commercial property  
- **luxury_assets_value** – Value of luxury assets  
- **bank_asset_value** – Value of bank savings/assets  

**Target Variable**:  
- **loan_status** (0 = Not Approved, 1 = Approved)  

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Cleaned and prepared the dataset.  
   - Mapped target labels into binary values (0/1).  

2. **Model Training**  
   - Implemented and compared two classifiers:  
     - Logistic Regression  
     - Random Forest Classifier  

3. **Model Evaluation**  
   - Accuracy Score  
   - Classification Report (Precision, Recall, F1-Score)  
   - Confusion Matrix  
   - Heatmap  
   - Feature Importance  

## 📊 Results  
The **Random Forest Classifier** outperformed Logistic Regression with an impressive accuracy of **98.3%**.  

**Classification Report (Random Forest):**  

| Metric      | Class 0 | Class 1 | Average |
|-------------|---------|---------|----------|
| Precision   | 0.97    | 0.99    | 0.98     |
| Recall      | 0.98    | 0.99    | 0.98     |
| F1-Score    | 0.98    | 0.99    | 0.98     |
| Accuracy    | -       | -       | **0.983** |  

## 📈 Visualizations  
- Confusion Matrix  
- Heatmap of Correlations  
- Feature Importance Plot  

These visualizations helped in understanding model performance and the impact of different features on predictions.  

## 🚀 Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## 📦 Installation & Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   cd loan-approval-prediction

2. Install dependencies:

pip install -r requirements.txt

3. Run the notebook:

jupyter notebook Loan_Approval_Prediction.ipynb

📌 Future Work

Deploy the model using Flask/Django with a frontend.

Integrate into a loan approval web application.

Try other advanced ML/DL models like XGBoost, LightGBM, or Neural Networks.

📝 License

This project is open-source and available under the MIT License.
