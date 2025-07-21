# 🛂 EasyVisa – Visa Approval Prediction using Machine Learning

This project leverages machine learning classification techniques to predict visa approval outcomes for foreign workers in the U.S., using data provided by the Department of Labor. The goal is to support data-driven workforce planning by identifying the most influential factors in visa certification decisions.

---

## 📌 Project Objective

To build predictive models that:
- Accurately classify whether a visa application will be certified or denied.
- Help U.S. companies proactively shortlist potential foreign workers.
- Identify key influencing features like education, wages, and work experience.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data wrangling and preprocessing
- **Scikit-learn** – ML model building and evaluation
- **Imbalanced-learn (SMOTE)** – Class balancing
- **Matplotlib, Seaborn** – Data visualization

---

## 🔍 Key Steps

1. **EDA & Preprocessing**
   - Cleaned and processed 25K+ visa records.
   - Handled missing values and engineered relevant features.

2. **Handling Imbalanced Data**
   - Applied SMOTE and undersampling techniques to address class imbalance.
   - Maintained focus on high recall to minimize false negatives.

3. **Model Building**
   - Trained multiple classifiers: Gradient Boosting, AdaBoost, XGBoost.
   - Tuned hyperparameters for optimal performance.
   - Achieved **93% recall**, prioritizing real-world business utility.

4. **Insights & Recommendations**
   - Identified key approval drivers: education level, wage offered, years of experience, job location.
   - Suggested practical actions for optimizing visa approval chances.

---

## 📈 Business Impact

- Reduced risk of denial by prioritizing high-recall predictions.
- Provided actionable insights for recruiters and immigration consultants.
- Supported strategic hiring in talent-scarce U.S. regions.

---

## 📁 Project Structure

