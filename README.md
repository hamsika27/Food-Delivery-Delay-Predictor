# 🚚 Food Delivery Delay Prediction

This project uses historical food delivery data to predict whether a delivery will be **on time or delayed** based on factors like discount offered, product weight, shipping mode, and more.

## 📌 Problem Statement
In food delivery services like Swiggy or Zomato, it's important to predict if a delivery might be delayed so the company can act early and improve customer satisfaction.

## 📁 Dataset
- **Source**: [Kaggle - https://www.kaggle.com/datasets/prachi13/customer-analytics?select=Train.csv
- Contains information such as:
  - Mode of shipment
  - Customer care calls
  - Customer rating
  - Cost of product
  - Discount offered
  - Product importance
  - Delivery time (Target column: `Reached.on.Time_Y.N`)

## ⚙️ Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Google Colab
- Machine Learning: Random Forest Classifier

## ✅ Tasks Performed
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Model Building and Evaluation
- Visualizations (confusion matrix, feature importance)

## 📈 Results
- Model Accuracy: ~66.7%
- Most important feature: `Discount_offered`

## 📌 Future Improvements
- Try other ML models (XGBoost, Logistic Regression)
- Hyperparameter tuning
- Build a Streamlit web app for real-time predictions

## 📂 How to Run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run `Food_Delivery_Delay_Prediction.ipynb` in Jupyter/Colab

## 🙋‍♀️ Author
**Hamsika P**  
LinkedIn - www.linkedin.com/in/hamsika-p-823838256

