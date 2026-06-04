# Bill Amount Prediction using Linear Regression

## Overview

This project uses a Linear Regression model to predict the tip amount based on the total bill amount.

The model is trained using historical restaurant billing data and can estimate the expected tip for a given bill amount.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## Machine Learning Workflow

1. Load the dataset from Excel
2. Data preprocessing
3. Remove unnecessary columns
4. Feature-target splitting
5. Train-test split
6. Train Linear Regression model
7. Evaluate model performance
8. Predict tip amount for new bill values

---

## Dataset Features

| Feature | Description |
|----------|-------------|
| Observed total bill(xi) | Total restaurant bill amount |
| Observed tip amount(yi) | Tip amount given by the customer |

---

## Model Used

- Linear Regression

---

## Performance Metrics

The model is evaluated using:

- Mean Squared Error (MSE)
- R² Score

---

## Features

- Data preprocessing
- Correlation analysis
- Model training and testing
- Performance evaluation
- Interactive bill amount prediction

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/A-b-h-i-n-a-V-01/Bill-Amount-Prediction-Regression-Model.git
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Run the notebook in Google Colab or Jupyter Notebook.

---

## Sample Input

```text
Enter Bill Amount : 50
```

## Sample Output

```text
Observed total bill    Predicted Tip Amount
50                     8.76
```

(Note: Output may vary depending on the trained model.)

---

## Learning Outcomes

- Data preprocessing
- Feature-target splitting
- Train-test splitting
- Linear Regression
- Model evaluation using MSE and R²
- Making predictions on new data

---

## Author

Abhinav Krishna C S

GitHub: https://github.com/A-b-h-i-n-a-V-01
