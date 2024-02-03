# Sampling in Machine Learning

Sampling is a critical aspect of the machine learning workflow, involving the selection of data points from a dataset for training, testing, and validation. Different sampling methods are employed to ensure that the selected data is representative and generalizable.

## Types of Sampling

### 1. Simple Random Sampling
Simple random sampling involves randomly selecting data points from the dataset, ensuring each data point has an equal chance of being included.

### 2. Systematic Sampling
Systematic sampling involves selecting every kth item from a list after an initial random starting point.

### 3. Stratified Sampling
Stratified sampling involves dividing the dataset into strata based on specific characteristics and then randomly selecting samples from each stratum.

### 4. Cross-Validation
Cross-validation is a technique where the dataset is partitioned into multiple subsets, and the model is trained and evaluated on different combinations of these subsets.

### 5. Bootstrap Sampling
Bootstrap sampling involves creating multiple subsets by sampling with replacement, allowing for the generation of multiple datasets for training and testing.

## Sampling in Machine Learning Models

In this project, we employed various sampling methods to assess the performance of five machine learning models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Results

After applying different sampling methods and evaluating the models, the Random Forest Classifier consistently showed the highest accuracy across various sampling techniques. This highlights the effectiveness of Random Forest in handling diverse sampling scenarios.

Feel free to explore the code and results in the associated files.
