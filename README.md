```markdown
# 🏙️ Mexico City Apartment Price Prediction

Predicting apartment prices in Mexico City (Distrito Federal) using location and size features.

## 📊 Results
| Metric | Value |
|--------|-------|
| Baseline MAE | $17,239 |
| Model MAE | $14,943 |
| Improvement | ~13% |

## 🔍 Key Finding
**Location beats size.** Borough (neighborhood) is the strongest price predictor —
Benito Juárez adds ~$13k to price while Tláhuac reduces it by ~$14k.

## 🛠️ Tech Stack
Python · Pandas · Scikit-learn · Matplotlib · Category Encoders

## ⚙️ Pipeline
1. **Wrangle** — Filter, clean, and engineer features from raw CSV files
2. **EDA** — Visualize price distribution and price vs. area
3. **Baseline** — Mean price as a naive benchmark
4. **Model** — OneHotEncoder → SimpleImputer → Ridge Regression
5. **Evaluate** — MAE comparison + feature importance chart
```
