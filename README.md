# Breast Cancer Classification Using K-Nearest Neighbors (KNN) with sklearn and Custom Implementation

## Description

This repository contains a Jupyter Notebook that demonstrates the classification of breast cancer tumors as either malignant or benign. The Breast Cancer Wisconsin Diagnostic Dataset is used for this purpose. Two approaches of K-Nearest Neighbors (KNN) algorithm are demonstrated: sklearn's KNN and a custom implementation of KNN.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [KNN Overview](#knn-overview)
- [Approaches](#approaches)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/KunalMamgain/CS235-KNN
    ```
2. Navigate to the project directory:
    ```
    cd CS235-KNN
    ```

## Usage
1. Open the Jupyter Notebook:
    ```
    jupyter notebook
    ```
2. Navigate to the notebook and run the cells to view the analysis and results.

## KNN Overview
- **Algorithm Steps**
    1. Load the labeled training dataset and choose the number of neighbors (`k`).
    2. For each new data point in the test dataset, calculate the distance to each of the training points and find the `k`-nearest neighbors.
    3. Classify the data point based on the majority label of the `k`-nearest neighbors.

- **Parameters**: The key parameter is `k`, the number of nearest neighbors.
  
- **Performance Metrics**: The algorithm is evaluated using accuracy, precision, recall, and F1-score.

## Approaches
- **Sklearn's KNN**: The sklearn library is used for a more automated and streamlined approach to solving the classification problem.
  
- **Custom KNN Implementation**: A custom-coded version of KNN is implemented to give more control over the algorithm and to understand its workings in depth.

## Results
Both sklearn's KNN and the custom KNN implementation are evaluated using Euclidean and Manhattan distance metrics. Detailed metrics like accuracy, precision, recall, and F1-score for each implementation can be found in the notebook.

## Contributing
If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## License
[MIT License](LICENSE)
