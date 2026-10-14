# Machine Learning Lab 2026

Semester 5 machine learning laboratory work. This repository contains Jupyter notebooks, datasets, and practical exercises covering Python fundamentals, data analysis, regression, classification, ensemble methods, and applied machine learning workflows.

## Repository overview

The project is organized into individual lab folders, each containing notebook(s) and the dataset(s) used for the exercise. The repository also includes a separate extra lab focused on image-based classification.

## Lab Contents

| Lab | Topics | Main files |
| --- | --- | --- |
| 1 | Descriptive statistics in Python: mean, median, mode, variance, and standard deviation | [lab 1 ML.ipynb](Lab%201/lab%201%20ML.ipynb) |
| 2 | NumPy arrays, arithmetic, aggregation, random values, dot products, sorting, and string operations | [lab 2 ML.ipynb](Lab%202/lab%202%20ML.ipynb) |
| 3 | Pandas data loading and inspection with Matplotlib visualizations using the Iris dataset | [lab 3 ML.ipynb](Lab%203/lab%203%20ML.ipynb), [Iris.csv](Lab%203/Iris.csv), [iris_dataset.csv](Lab%203/iris_dataset.csv) |
| 4 | USA house-price prediction and regression analysis | [lab4.ipynb](Lab%204/lab4.ipynb), [USA_Housing - USA_Housing.csv](Lab%204/USA_Housing%20-%20USA_Housing.csv) |
| 5 | Binary Iris classification with logistic regression and evaluation metrics including accuracy, error rate, Cohen's kappa, precision, recall, F1 score, and confusion matrix | [Lab5ML.ipynb](Lab%205/Lab5ML.ipynb), [iris_data.csv](Lab%205/iris_data.csv) |
| 6 | Support Vector Machine classification using linear, polynomial, and Gaussian RBF kernels | [lab.ipynb](Lab%206/lab.ipynb), [iris_dataset_SVM - iris_dataset_SVM.csv](Lab%206/iris_dataset_SVM%20-%20iris_dataset_SVM.csv) |
| 7 | Multi-class Iris classification with `MLPClassifier` and different hidden-layer configurations | [lab.ipynb](Lab%207/lab.ipynb), [iris_dataset_MLP - iris_dataset_MLP.csv](Lab%207/iris_dataset_MLP%20-%20iris_dataset_MLP.csv) |
| 8 | Gaussian discriminant analysis with LDA, QDA, and class-distribution plots | [lab8.ipynb](Lab%208/lab8.ipynb), [iris_dataset_GDA - iris_dataset_GDA.csv](Lab%208/iris_dataset_GDA%20-%20iris_dataset_GDA.csv) |
| 9 | Gaussian Naive Bayes classification with training/testing accuracy and classification report | [lab9.ipynb](Lab%209/lab9.ipynb), [iris_dataset_NB.csv](Lab%209/iris_dataset_NB.csv) |
| 10 | Random forest classification and ensemble learning | [lab10.ipynb](Lab%2010/lab10.ipynb), [iris_dataset_RF.csv](Lab%2010/iris_dataset_RF.csv) |
| 11 | AdaBoost learning, ensemble boosting, and model evaluation | [lab11.ipynb](Lab%2011/lab11.ipynb), [Assignment_Adaboost_learning.ipynb](Lab%2011/Assignment_Adaboost_learning.ipynb), [iris_dataset_Adaboost.csv](Lab%2011/iris_dataset_Adaboost.csv) |
| Extra Lab 1 | Image classification exercise using cat/dog image data | [extralab1.ipynb](Extra%20Lab%201/extralab1.ipynb), [PetImages](Extra%20Lab%201/PetImages) |

## Getting started

1. Install Python 3 and Jupyter.
2. Create and activate a virtual environment if desired.
3. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

4. Open the notebook from its lab folder so that relative dataset paths resolve correctly.

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

## Notes

- Some lab folders contain multiple notebook files or copies of the same exercise; the main notebook for each lab is listed above.
- Datasets are stored alongside the notebooks and should be opened from the corresponding lab directory.
