# Breast Cancer Classification Using K-Nearest Neighbors (KNN) with sklearn and Custom Implementation

## Description

This repository contains a Jupyter Notebook that demonstrates the classification of breast cancer tumors as either malignant or benign, using the Breast Cancer Wisconsin Diagnostic Dataset. The project explores two different implementations of the K-Nearest Neighbors (KNN) algorithm: one using sklearn's KNN and another using a custom-coded KNN.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [KNN Overview](#knn-overview)
- [Approaches](#approaches)
- [Experimental Setup](#experimental-setup)
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
- **Sklearn's KNN**: Utilizes the sklearn library for a more automated and streamlined approach to solving the classification problem.
  
- **Custom KNN Implementation**: A custom-coded version of KNN is implemented to provide more control over the algorithm and to understand its workings in depth.

## Experimental Setup
- Utilized two different distance functions: Euclidean and Manhattan.
- Employed two different classes of feature representations:
    1. Low rank approximation of the data using Singular Value Decomposition (SVD) at both low and high approximation ranks.
    2. Feature representation using an off-the-shelf MLP-based AutoEncoder with different bottleneck layer sizes (5% and 20% of the original number of features).

## Results
Both sklearn's KNN and the custom KNN implementation were evaluated using Euclidean and Manhattan distance metrics. Detailed metrics like accuracy, precision, recall, and F1-score for each implementation can be found in the notebook. For more in-depth evaluation, you can read the [paper](https://drive.google.com/file/d/1wYpZPeY1WuLoQ6YWc8KJFsRMAV-YJO3x/view?usp=drive_link).

## Contributing
If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## License
[MIT License](LICENSE)

