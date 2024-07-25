# Breast Cancer Classification

This repo utilises various classification models, such as Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Random Forest, to classify breast cancer malignancy using the Wisconsin Breast Cancer dataset.

## Dataset

The Wisconsin Breast Cancer dataset is used for this project. The dataset is available from the UCI Machine Learning Repository and contains 569 samples with 32 feature columns and a target column indicating the diagnosis (malignant or benign).

- **Features**: Various characteristics of the cell nuclei present in the digitized image of a fine needle aspirate (FNA) of a breast mass.
- **Target**: Diagnosis of breast tissue (M = malignant, B = benign).

## Models

The following machine learning models are implemented and compared:

1. **Support Vector Machine (SVM)**: A supervised learning model that analyzes data for classification and regression analysis.
2. **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that assigns a class based on the majority class among the k-nearest neighbors.
3. **Random Forest**: An ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes of the individual trees.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Jam-Cai/Wisconsin_Breast_Cancer_DataSet.git
cd Wisconsin_Breast_Cancer_DataSet
pip install -r requirements.txt
```
