This Repository contains Random Forest Classifier Algorithm from the scratch without using the dependencies Scikit Learn,NumPY,Pandas

Implementation Details
Initialization: The __init__ method sets up the parameters for the random forest, including the number of trees, maximum depth, and minimum samples required for a split.
Training: The fit method trains each decision tree on a different bootstrap sample of the data. The trained trees are stored in a list.
Prediction: The predict method aggregates the predictions from all trees and determines the final class label for each sample by majority voting.
Advantages
Improved Accuracy: The ensemble approach reduces overfitting and improves generalization.
Versatility: Can handle large datasets with higher dimensionality.
Robustness: The model is less sensitive to noisy data and outliers.
Dependencies
numpy: Used for array operations and random sampling.
DecisionTreeClassifier: Assumes a separate implementation of a decision tree classifier is available.
