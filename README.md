# VLSI Timing Slack Prediction using Machine Learning

## Overview

This project predicts timing slack in VLSI circuits using Machine Learning. Instead of relying solely on computationally intensive timing analysis, a Random Forest Regression model is trained to estimate timing slack based on circuit features.

The objective is to identify potential timing violations efficiently and support faster design optimization during the VLSI design flow.

---

## Features

- Predicts timing slack using Random Forest Regression
- Performs data preprocessing and feature engineering
- Evaluates model performance using standard regression metrics
- Visualizes prediction accuracy and feature importance
- Demonstrates the use of Machine Learning in Electronic Design Automation (EDA)

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## Project Workflow

1. Import Dataset
2. Data Preprocessing
3. Feature Selection
4. Train/Test Split
5. Random Forest Model Training
6. Model Evaluation
7. Performance Visualization

---

## Results

Example metrics:

- R² Score: 0.84
- Mean Squared Error: 11.4
- Accurate prediction of timing violation

---

## Repository Structure

```
README.md
requirements.txt
vlsi_timing_slack_prediction.ipynb
sample_dataset.csv
images/
docs/
```

---

## Future Improvements

- XGBoost Regression
- LightGBM
- Graph Neural Networks
- Deep Learning Models
- Larger benchmark datasets

---

## Author

**Ajay Mandadapu**

Electronics and Communication Engineering Student

Interested in:
- VLSI Design
- Hardware Security
- Embedded Systems
- Machine Learning
- IoT

---

## License

This project is licensed under the MIT License.
