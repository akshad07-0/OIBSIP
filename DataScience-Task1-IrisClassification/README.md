# Task 1: Iris Flower Classification

**Intern:** Akshad Rakesh Jaiswal
**Track:** Data Science
**Program:** Oasis Infobyte Summer Internship Program (OIBSIP)

## Objective
Train a machine learning classification model to identify the species of an
iris flower (Setosa, Versicolor, or Virginica) from its physical measurements.

## Dataset
The built-in Iris dataset from `sklearn.datasets` (150 samples, 4 numeric
features, 3 balanced classes).

## Tech Stack
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## Approach
1. Loaded the Iris dataset and performed EDA (shape, dtypes, null check, descriptive statistics).
2. Visualised feature relationships using a pairplot and box plots per species.
3. Split the data into 80% train / 20% test sets (stratified by species).
4. Trained two classifiers: Logistic Regression and K-Nearest Neighbours (KNN).
5. Evaluated both models using accuracy, confusion matrix, and classification report.

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 96.67% |
| K-Nearest Neighbours | 100% |

KNN performed best on this test split, correctly classifying all 30 test
samples. Petal length and petal width were the most useful features for
separating the species, while sepal width showed the most overlap between
Versicolor and Virginica.

## How to Run
1. Open `Task1_Iris_Classification.ipynb` in Google Colab or Jupyter.
2. Run all cells in order (Runtime → Run all).
3. No external dataset download is required — the Iris dataset is built into scikit-learn.

## Files
- `Task1_Iris_Classification.ipynb` — full notebook with EDA, visualisations, model training, and evaluation.
