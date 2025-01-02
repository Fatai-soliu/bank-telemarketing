# Preidicting Student Dropout and Academic Success

Link to Dataset: https://archive.ics.uci.edu/dataset/222/bank+marketing

# Project 1: Predicting Student Dropout and Academic Success with KNN and Decision Tree
This project evaluates machine learning models to predict student dropout and academic success, aiming to enhance educational retention strategies.

# What I Did

Analyzed a dataset of 4,424 students with 37 features, including demographics, academic, and economic metrics.
Preprocessed data by handling class imbalance (SMOTE), standardization, and recursive feature elimination to optimize features.
Implemented and compared Decision Tree and KNN classifiers, using GridSearchCV for hyperparameter tuning.

# Tools and Techniques 
Python (Pandas, NumPy, Scikit-learn) for modeling and evaluation.
Visualization with Matplotlib and Seaborn.
SMOTE for addressing class imbalance.

# Results 

KNN: 71.4% accuracy, outperforming Decision Tree in precision, recall, and F1-score.
Decision Tree: 66.5% accuracy, less effective in handling minority classes.

# My Key Takeaways
KNN's performance and balanced metrics make it suitable for identifying at-risk students, while Decision Trees may require further tuning for improved accuracy.


Here’s a concise summary for each project in your report, personalized for a GitHub README format:

1. Predicting Student Dropout and Academic Success with KNN and Decision Tree
This project evaluates machine learning models to predict student dropout and academic success, aiming to enhance educational retention strategies.

What I Did

Analyzed a dataset of 4,424 students with 37 features, including demographics, academic, and economic metrics.
Preprocessed data by handling class imbalance (SMOTE), standardization, and recursive feature elimination to optimize features.
Implemented and compared Decision Tree and KNN classifiers, using GridSearchCV for hyperparameter tuning.
Tools and Techniques I Used

Python (Pandas, NumPy, Scikit-learn) for modeling and evaluation.
Visualization with Matplotlib and Seaborn.
SMOTE for addressing class imbalance.
Results I Achieved

KNN: 71.4% accuracy, outperforming Decision Tree in precision, recall, and F1-score.
Decision Tree: 66.5% accuracy, less effective in handling minority classes.
My Key Takeaways
KNN's performance and balanced metrics make it suitable for identifying at-risk students, while Decision Trees may require further tuning for improved accuracy.

# Project 2. Customer Segmentation in Bank Telemarketing Using K-Means and Hierarchical Clustering
This project applies clustering algorithms to segment customers, improving telemarketing campaign effectiveness.

# What I Did
Processed a telemarketing dataset with customer demographics, financials, and campaign interactions.
Applied EDA, handled outliers with the IQR method, and standardized features for consistency.
Implemented K-Means (k=3) and Hierarchical Clustering, evaluating clusters using silhouette scores.

# Tools and Techniques

Python (Scikit-learn, Matplotlib, Seaborn).
Clustering methods (K-Means, Hierarchical Clustering).
Elbow method and dendrogram visualization for cluster analysis.

# Results

K-Means: Silhouette score of 0.53, clearly segmented high-income, low-income, and middle-income clusters.
Hierarchical Clustering: Silhouette score of 0.47, better at revealing nested relationships but less distinct clusters.

# My Key Takeaways
K-Means provides clear and interpretable clusters for targeting campaigns, while Hierarchical Clustering offers deeper insights into inter-cluster relationships.
