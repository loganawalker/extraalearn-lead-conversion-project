# 🧠 ExtraaLearn Lead Conversion Prediction & Lead Scoring

This project analyzes lead behavior data for ExtraaLearn, an EdTech startup, to predict which leads are most likely to convert and assign a lead score for prioritization. It uses a Random Forest classifier for prediction and a weighted behavioral scoring model to segment leads into actionable tiers.

---

## 📊 Project Features

- 🔍 Exploratory Data Analysis (EDA) – Univariate & Bivariate
- 🌲 Decision Tree & Random Forest Models
- 🎯 Model Tuning via GridSearchCV
- 🧮 Feature Importance Ranking
- 📈 Lead Scoring System (0–100)
- 🔥 Tier Segmentation: Hot, Warm, Cold, Very Cold
- 📤 Exportable Predictions for Business Teams

---

## 🧪 Files Included

| File                                      | Description                                      |
|-------------------------------------------|--------------------------------------------------|
| `Final_Project_Potential_Customers_Prediction.ipynb` | Full notebook with modeling, EDA, visuals, and insights |
| `Final_Project_Potential_Customers_Prediction.html`  | HTML export for presentation/report              |
| `lead_conversion_model.pkl`              | Trained Random Forest model                      |
| `lead_score_scaler.pkl`                  | MinMaxScaler used for scoring normalization      |
| `final_lead_data_with_scores.csv`        | Dataset with scores, predictions, and tiers      |
| `lead_score_histogram.png`               | Histogram of lead score distribution             |
| `lead_tier_breakdown.png`                | Bar chart of lead tier counts                    |
| `roc_curve.png`                          | ROC Curve showing model performance              |
| `Lead_Tier_Summary.csv`                  | Optional: tier-level lead summary                |
| `lead_scoring_template.py` (or `.ipynb`) | Template for future predictions and scoring      |

---

## 🚀 How to Use the Lead Scoring Template

1. Clone or download this repo
2. Upload new leads CSV (`new_leads.csv`)
3. Run `lead_scoring_template.ipynb` or `.py`
4. It will:
   - Load the model and scaler
   - Predict conversion
   - Assign scores and tiers
   - Export the results as CSV

---

## 📊 Tier Buckets

| Tier         | Score Range | Action                                  |
|--------------|-------------|------------------------------------------|
| Hot          | 80–100      | Prioritize for immediate follow-up       |
| Warm         | 60–79       | Retarget with personalized outreach      |
| Cold         | 40–59       | Nurture with automated drip campaigns    |
| Very Cold    | <40         | Low priority or recycle in future        |

---

## 📈 Model Performance

- Accuracy: **86.3%**
- AUC Score: *Displayed in ROC Curve*
- Evaluation Metrics: Precision, Recall, F1-score, Confusion Matrix

## 📌 Requirements

- Python ≥ 3.8  
- `pandas`, `numpy`, `joblib`, `scikit-learn`, `matplotlib`, `seaborn`

You can install them with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```


✍️ Author
**Logan Walker**
MIT Project – ExtraaLearn Lead Conversion Modeling
March 2025

📧 walker.la29@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/logan-a-walker/) | [GitHub](https://github.com/loganawalker) 


















