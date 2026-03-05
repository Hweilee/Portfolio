# Portfolio

My personal work to demonstrate my Python data analysis workflow in Google Colab.

## Project: Shopper Behavior Analysis

**Notebook:** `Shopper_behaviour (1).ipynb`

### Overview

This project explores shopper/customer behavior using Python. It includes:

* Data loading and basic data checks (shape, types, missing values)
* Cleaning and converting Yes/No fields into binary values
* Segment analysis: subscription rate by different customer attributes (e.g., age group, gender, category, season, shipping, payment, location — depending on the dataset columns)
* Promo code usage vs subscription relationship (cross-tab counts and rate comparison)
* A simple baseline machine learning model (Random Forest) to predict **Subscription Status**
* Model evaluation (classification report, confusion matrix)
* Feature importance to interpret which factors most influence subscription prediction

### Key Outputs (in the notebook)

* Summary tables (groupby / crosstab)
* Plots for subscription rates by segment
* Confusion matrix + classification report
* Feature importance chart

---

## How to Run

### Option A — Google Colab (recommended)

1. Open `Shopper_behaviour (1).ipynb` in Colab
2. Upload the dataset CSV when prompted (or update the file path in the notebook)
3. Run all cells top to bottom

### Option B — Local Jupyter

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

---

## Dataset Notes

* Dataset file is **not included** in this repository unless it is permitted to be shared publicly.
* Expected columns may include fields like:

  * `Subscription Status`
  * `Promo Code Used`
  * and other demographic/transaction attributes (dataset dependent)

---

## Skills Demonstrated

* Python (pandas, numpy)
* Data cleaning & type conversion
* EDA and grouped analysis (groupby / crosstab)
* Visualization (matplotlib / seaborn)
* Baseline ML modeling (scikit-learn RandomForest)
* Model evaluation + interpretation (feature importance)

---

## Next Improvements

* Add percentage tables consistently (row-wise / column-wise) for every key comparison
* Try Logistic Regression as a baseline and compare performance
* Add simple statistical test (e.g., chi-square) for Promo Code vs Subscription association



