# Edutech_Data_Science_Task5
## Logistic Regression Binary Classification Model
This project implements a binary classification pipeline using Logistic Regression to predict whether a breast cancer tumour is Malignant (1) or Benign (0).

## Workflow Steps Implemented
* **Data Cleaning:** Handled and dropped unnecessary columns (`id` and `Unnamed: 32`).
* **Binary Classification / Label Encoding:** Converted the categorical text column `diagnosis` ('M' and 'B') into binary numerical values (0 and 1) using `LabelEncoder`.
* **Data Splitting:** Partitioned the dataset into 80% Training and 20% Testing subsets.
* **Feature Scaling:** Normalised the input features using `StandardScaler` to ensure optimal performance and avoid convergence warnings.
* **Model Training:** Initialised and trained a standard `LogisticRegression` model via `scikit-learn`.
* **Evaluation:** Successfully evaluated the model performance using the Accuracy Score and a detailed Classification Report.

## Deliverables Included
* `Edutech_Data_Science_Task5.ipynb` - Complete Python Source Code Notebook
* `data.csv` - The processed Breast Cancer Dataset
