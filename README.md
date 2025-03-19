# Breast Cancer Classification with K-Nearest Neighbors

## Overview
This simple project implements a K-Nearest Neighbors classifier to predict breast cancer diagnoses using the `sklearn` dataset. The classifier's accuracy is evaluated for different values of `k`, and the results are visualized using a plot.

## Dataset
The dataset used is the **Breast Cancer Wisconsin dataset**, which is available in `sklearn.datasets`. It contains:
- Features representing characteristics of cell nuclei (e.g., mean radius, mean texture, etc.)
- Target labels:
  - `0`: Malignant
  - `1`: Benign

## Installation
Ensure you have Python and the required libraries installed. You can install the necessary dependencies using:
```sh
pip install scikit-learn matplotlib seaborn
```

## Code Explanation
1. **Loading the dataset**: The `load_breast_cancer` function is used to load the dataset.
2. **Splitting the data**: The dataset is divided into training and validation sets using `train_test_split`.
3. **Training the classifier**: A `KNeighborsClassifier` is trained for values of `k` ranging from 1 to 100.
4. **Evaluating accuracy**: The accuracy of the classifier is computed for each `k` and stored in a list.
5. **Visualization**: The accuracy is plotted against `k` using `matplotlib`.

## Usage
Run the script using:
```sh
python script.py
```
This will generate a plot showing how the validation accuracy varies with different values of `k`.

## Output
The program produces a plot titled **"Breast Cancer Classifier Accuracy"**, displaying the accuracy of the model for different values of `k`.

## License
This project is released under the MIT License.

