# 🫁 Lungs Disease Prediction  

This project uses machine learning algorithms to predict the severity or presence of lung diseases based on various patient attributes. The dataset provides insights into health and environmental factors influencing lung health.  

---

## 📋 **Dataset Overview**  

The dataset contains patient information and health-related features contributing to lung disease prediction.  

### **Columns**  
| **Feature**                 | **Description** |  
|------------------------------|-----------------|  
| `Index`                     | Row index for the dataset. |  
| `Patient Id`                | Unique identifier for each patient. |  
| `Age`                       | Patient's age. |  
| `Gender`                    | Gender of the patient. |  
| `Air Pollution`             | Exposure to air pollution. |  
| `Alcohol use`               | Alcohol consumption levels. |  
| `Dust Allergy`              | Sensitivity to dust. |  
| `Occupational Hazards`      | Risks associated with the patient’s occupation. |  
| `Genetic Risk`              | Genetic predisposition to lung diseases. |  
| `Chronic Lung Disease`      | History of chronic lung issues. |  
| ...                         | Additional health and lifestyle factors. |  
| `Fatigue`                   | Presence of fatigue symptoms. |  
| `Weight Loss`               | Unexplained weight loss. |  
| `Shortness of Breath`       | Difficulty in breathing. |  
| `Wheezing`                  | High-pitched whistling sound while breathing. |  
| `Swallowing Difficulty`     | Trouble swallowing. |  
| `Clubbing of Finger Nails`  | Nail bed deformities. |  
| `Frequent Cold`             | Recurring cold symptoms. |  
| `Dry Cough`                 | Persistent dry cough. |  
| `Snoring`                   | Frequency of snoring. |  
| `Level`                     | Target variable indicating lung disease severity. |  

---

## 📊 **Workflow**  

1. **Exploratory Data Analysis (EDA):**  
   - Visualized distributions of patient features like `Age`, `Gender`, `Air Pollution`, and `Chronic Lung Disease`.  
   - Analyzed the correlation between health and environmental factors with the `Level` (lung disease severity).  

2. **Modeling:**  
   - Implemented three machine learning algorithms to predict lung disease severity:  
     - **XGBoost**  
     - **AdaBoost**  
     - **Random Forest (RF)**  

3. **Performance Metrics:**  
   - Evaluated models using **accuracy scores** to compare their effectiveness.  

---

## 🎯 **Results**  

| **Model**        | **Accuracy** |  
|-------------------|--------------|  
| **XGBoost**      | **100%**    |  
| **Random Forest** | **100%**    |  
| **AdaBoost**      | 74%         |  

- Both **XGBoost** and **Random Forest** achieved perfect prediction accuracy, showcasing their suitability for this dataset.  
- **AdaBoost** performed moderately well, with a **74% accuracy**, highlighting its sensitivity to data distribution.  

---

## 🛠️ **Tools and Techniques**  

- **Libraries Used:** `pandas`, `NumPy`, `Matplotlib`, `seaborn`, `xgboost`, `scikit-learn`  
- **Models Implemented:**  
  - **XGBoost**: Gradient boosting method optimized for performance.  
  - **Random Forest**: Ensemble method using decision trees.  
  - **AdaBoost**: Adaptive boosting technique to improve weak learners.  

---

## ✨ **Key Takeaways**  

- **Feature importance** plays a crucial role in predicting lung diseases, especially environmental and genetic factors.  
- **XGBoost** and **Random Forest** are highly effective in handling complex, feature-rich datasets.  
