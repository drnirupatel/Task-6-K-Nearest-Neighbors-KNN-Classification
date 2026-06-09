# Task 6 - KNN Classification

## Objective
Implement K-Nearest Neighbors (KNN) Classification using the Iris Dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

## Steps Performed
1. Loaded Iris Dataset.
2. Split data into training and testing sets.
3. Normalized features using StandardScaler.
4. Trained KNN classifier.
5. Tested multiple K values.
6. Evaluated model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
7. Visualized K vs Accuracy.
8. Visualized Decision Boundary.

## Results

Model Accuracy: 93.33%

Confusion Matrix:

[[10 0 0]
 [0 10 0]
 [0 2 8]]

Key Observations:
- Iris-setosa was classified perfectly.
- Iris-versicolor achieved 100% recall.
- Two Iris-virginica samples were misclassified as Iris-versicolor.
- Overall model performance was strong with 93.33% accuracy.
