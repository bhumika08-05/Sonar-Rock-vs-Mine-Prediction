# Sonar Rock vs Mine Prediction

## Overview

This project uses Machine Learning to predict whether an object detected by sonar signals is a Rock or a Mine. The model is trained on the Sonar dataset and uses Logistic Regression for classification.

The goal of this project is to analyze sonar signal data and build a predictive model that can accurately classify underwater objects.

---

## Dataset Information

The dataset contains sonar signal readings collected from objects underwater.

* Total Features: 60
* Target Variable:

  * R = Rock
  * M = Mine

Each record contains numerical values representing sonar signal strengths returned from different angles and frequencies.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Perform data analysis
4. Separate features and target labels
5. Split data into training and testing sets
6. Train Logistic Regression model
7. Evaluate model accuracy
8. Predict whether an object is a Rock or Mine

---

## Libraries Used

```python
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
```

---

## Model Used

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems. It predicts the probability of an input belonging to a particular class.

In this project:

* Class R = Rock
* Class M = Mine

---

## Project Structure

```text
Sonar-Rock-vs-Mine-Prediction
│
├── sonar_rock vs mine prediction.ipynb
├── sonar_data.csv
└── README.md
```

---

## How to Run

1. Clone or download the repository.
2. Install required libraries:

```bash
pip install numpy pandas scikit-learn jupyter
```

3. Open Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all notebook cells.

---

## Sample Output

```text
Accuracy on training data : 85%+
Accuracy on test data : 75%+ 
```

The model predicts whether the given sonar signal belongs to a Rock or a Mine.

---

## Learning Outcomes

Through this project I learned:

* Data preprocessing using Pandas
* Exploratory Data Analysis
* Train-Test Split
* Logistic Regression
* Model Evaluation
* Accuracy Measurement
* Machine Learning Workflow

---

## Future Improvements

* Use Random Forest Classifier
* Use Support Vector Machine (SVM)
* Perform Hyperparameter Tuning
* Create a Web Application using Streamlit
* Improve Prediction Accuracy

---

## Author

Bhumika Rai

B.Tech Student | Machine Learning Enthusiast
