# Customer Churn Prediction

This project focuses on building a machine learning model to predict customer churn using classification techniques. The goal is to help businesses proactively identify customers at risk of leaving so that they can take steps to improve retention.

## 🔍 Project Overview

- **Notebook:** [project17.ipynb](https://github.com/cliiiiine/churn_prediction/blob/main/project17.ipynb)
- **Report:** [project17_report.ipynb](https://github.com/cliiiiine/churn_prediction/blob/main/project17_report.ipynb)

We used an imbalanced dataset simulating customer behaviors to:
- Explore feature distributions
- Engineer predictive features
- Train and evaluate multiple models
- Optimize thresholds to prioritize recall

## 🧠 Key Concepts

- Binary classification
- Imbalanced data handling
- Feature engineering
- Model evaluation with precision, recall, and F1-score
- Threshold tuning for business alignment

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Model Performance

We prioritized **recall** over precision to capture as many potential churners as possible, minimizing customer loss. The final model achieved:

- **Recall:** 0.94
- **Precision:** 0.41
- Threshold adjusted to 0.1 to improve recall

## 📈 Insights & Strategy

While the model had moderate precision, it effectively captured most churners — aligning with the business goal of retention over short-term marketing costs. We recommend using this model to trigger retention offers and follow-up strategies.

## 🗂️ File Structure

- `project17.ipynb`: Main notebook with EDA, feature selection, modeling
- `project17_report.ipynb`: Condensed report with key findings and model results
- `README.md`: Project overview and usage details

## 💡 Future Improvements

- Add SHAP or LIME for interpretability
- Explore cost-sensitive learning
- Collect more representative data for better generalization

## 🙋🏽‍♀️ About Me

Created by **Keith Robinson**, Data Analyst transitioning into Data Science. Passionate about building models that drive strategic decisions in marketing, compliance, and customer retention.

Connect with me on [LinkedIn](https://www.linkedin.com/in/keithcr/).

---

