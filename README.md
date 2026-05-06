# Biomedical_mini_pipeline
This project contains a single Python script, `biomedical_pipeline.py`, which implements a small end‑to‑end biomedical data analysis workflow.
It is designed as a simple, beginner‑friendly example of how to structure a basic pipeline in Python.

# Features
* **Dataset loading:** Breast Cancer Wisconsin dataset from *sickit-learn*.
* **Preprocessing:** standardization of numerical features.
* **Exploratory analysis:** dataset info, descriptive statistics.
* **Visualizations:**
    * Class distribution
    * Correlation heatmap
    * Histograms of different variables
    * Mean radius vs target relation
* **Modeling:** logistic regression baseline.
* **Evaluation:** accuracy and confusion matrix.

# Dependencies
You can install the required packages with:
```bash
pip install pandas seaborn matplotlib sickit-learn
```

# Running the script
Make sure you have the required libraries installed, then run:
```bash
python biomedical_pipeline.py
```
