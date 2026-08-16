# Dataset Bias Detector and Corrector using Responsible AI

## Overview

This project detects bias in a loan approval dataset and applies Responsible AI techniques to reduce unfairness while maintaining high machine learning performance.

The system measures fairness before and after bias correction using standard fairness metrics and trains a Random Forest classifier on the corrected data.

## Features

- Detects gender bias in loan approval datasets
- Calculates fairness metrics (DIW and DPD)
- Applies Reweighing algorithm for bias correction
- Trains Random Forest classifier
- Performs 5-Fold Cross Validation
- Generates classification report
- Displays confusion matrix
- Shows feature importance
- Creates visualization dashboard
- Exports the de-biased dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google colab


## Dataset

- Records: 5,000
- Features: 12


## Fairness Metrics

### Before Correction

- DIW: 0.0560
- DPD: -0.6286

### After Correction

- DIW: 1.0000
- DPD: 0.0000


## Model Performance

- Accuracy: 95.80%
- ROC-AUC: 0.9935
- Cross Validation Accuracy: 96.06%
- Cross Validation AUC: 0.9943


## Project Structure

Dataset_Bias_Detector_and_Corrector/

├── notebooks/

├── dataset/

├── screenshots/

├── README.md

├── requirements.txt

└── .gitignore


## How to Run

1. Clone this repository.
2. Install the required packages.

```
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Run all cells.


## Output

The project generates:

- Fairness metrics before and after correction
- Model evaluation metrics
- Feature importance analysis
- Visualization dashboard
- De-biased dataset

## Author

Kayalvizhi S

B.E. Artificial Intelligence and Machine Learning
