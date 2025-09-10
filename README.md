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
