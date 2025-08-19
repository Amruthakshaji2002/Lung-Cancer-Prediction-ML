
# 🫁 Lung Cancer Prediction using Machine Learning  

A machine learning project to predict the likelihood of lung cancer based on patient lifestyle and medical attributes.  
The system compares multiple ML algorithms and deploys the best-performing model (Logistic Regression) via a Flask web application.  

---

## 📌 Project Overview  
Lung cancer is one of the leading causes of cancer-related deaths worldwide. Early detection plays a crucial role in improving survival rates.  
This project leverages **machine learning classification models** to predict whether a patient is likely to develop lung cancer.  

---

## 🎯 Objectives  
- Build and compare multiple classification models for lung cancer prediction.  
- Identify the most accurate model for deployment.  
- Create a user-friendly web app to input patient data and generate predictions.  

---

## 📊 Dataset  
- Source: [Kaggle – Survey Lung Cancer Dataset](https://data.world/sta427ceyin/survey-lung-cancer)  
- Size: **391 samples**  
- Features (15 total):  
  - Age, Gender, Smoking, Anxiety, Wheezing, Yellow Fingers, Fatigue, Alcohol Consuming, Peer Pressure, Coughing, Shortness of Breath, Swallowing Difficulty, Allergy, Chest Pain, Chronic Diseases  
- Target: **Lung Cancer Severity (Low, Average, Critical)**  

---

## 🧠 Methodology  
1. **Data Preprocessing**: Handling missing values, encoding categorical features, normalization  
2. **Model Training**: Logistic Regression, Decision Tree, Random Forest, XGBoost, Gradient Boosting, SVC, KNN  
3. **Evaluation**: Train/test split (80/20), accuracy comparison  
4. **Deployment**: Flask web app for interactive predictions  

---

## 📈 Results  

| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression | **0.94** |
| XGBoost            | 0.92     |
| SVC                | 0.91     |
| Decision Tree      | 0.91     |
| Gradient Boosting  | 0.91     |
| KNN                | 0.89     |
| Random Forest      | 0.85     |

✅ Logistic Regression gave the highest accuracy.  

---

## 📷 Sample Web App Screenshots  

<p align="center">
  <img src="images/prediction_status1.png" width="350">
  <img src="images/prediction_status2.png" width="350">
</p>

---

## 🔮 Future Scope  
- Add deep learning models (CNN, ANN) for improved accuracy  
- Integrate medical imaging (X-rays, CT scans)  
- Deploy as a cloud-based service or mobile app  

---

## 📂 Repository Structure  
