# NFL Draftability Prediction Model

This project predicts whether a college football player will be **drafted** or **not drafted** into the NFL using their **NFL Combine performance metrics**.  
It demonstrates applied machine learning with real sports data, feature engineering, and model evaluation.

---

## Try It Yourself

Click below to run the notebook interactively in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/eshaanraj/nfl_draft_model/blob/main/nfl_draftability.ipynb)

---

## Project Overview

- **Goal**: Predict draftability of players from NFL Combine data.  
- **Inputs**: Combine metrics (40-yard dash, bench press, vertical jump, shuttle times, height, weight, etc.).  
- **Output**: Binary classification → `Drafted` (Yes) or `Not Drafted` (No).  
- **Methods**: Decision Tree and Random Forest classifiers.  
- **Why it matters**: Shows how measurable athletic performance correlates with draft outcomes, and illustrates how ML can support sports analytics.

---

## How to Run

### Option A — In Colab (easiest)
1. Open the notebook using the badge above.  
2. Upload the dataset CSV when prompted (`NFL.csv`).  
3. Run all cells.

### Option B — Locally
1. Clone the repository:  
   ```bash
   git clone https://github.com/eshaanraj/nfl_draft_model.git
   cd nfl_draft_model
   
## Results
# Decision Tree
- Cross-validation mean: 0.652 ± 0.022
- Accuracy: 0.652
- Tends to underperform vs. Random Forest, but provides interpretability.

# Random Forest
- Accuracy: 0.703
- Precision/Recall:
- Drafted (Yes): Precision 0.74, Recall 0.84, F1 = 0.78
- Not Drafted (No): Precision 0.60, Recall 0.46, F1 = 0.52

# Key Features
- Sprint_40yd 
- Age
- Weight
- BMI

# Example Output
<img width="1194" height="797" alt="image" src="https://github.com/user-attachments/assets/ca4c40c9-7e2b-48fa-ba58-37d7b27895b2" />

## Dataset
This project uses the dataset:
NFL Combine Performance Data (2009–2019) by redlineracer
Available on Kaggle
# Contains player combine results (40-yard dash, bench press, vertical jump, etc.) and draft outcomes.
# Data spans 2009–2019 NFL Drafts.
# Licensed and shared publicly on Kaggle.
