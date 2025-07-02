# Task-5--AI-ML
 Setup and Data Loading
Libraries Imported:
pandas for data manipulation.
sklearn.model_selection for train_test_split and cross_val_score.
sklearn.tree for DecisionTreeClassifier and export_graphviz.
sklearn.ensemble for RandomForestClassifier.
sklearn.metrics for accuracy_score.
graphviz for visualizing the decision tree (requires external Graphviz installation).
matplotlib.pyplot for plotting.
numpy for numerical operations, especially with cross-validation scores.
Data Loading: The heart.csv dataset is loaded into a pandas DataFrame.
Feature and Target Separation:
X (features) contains all columns except 'target'.
y (target) contains the 'target' column.
Data Splitting: The data is split into training (70%) and testing (30%) sets using train_test_split to evaluate model performance on unseen data.
