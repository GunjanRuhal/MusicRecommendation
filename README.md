# Music & Mental Well-being: An ML Classification & Genre Insights Project
This project explores the intricate relationship between music listening habits, genre preferences, and their reported impact on various mental health conditions (Anxiety, Depression, Insomnia, and OCD) using a comprehensive survey dataset. It employs machine learning classification models to predict how music affects an individual's mental well-being and derives data-driven genre insights for specific conditions.

# Project Goal
To analyze survey data, build classification models to predict whether music has a positive or non-positive effect on mental well-being, and identify music genres that correlate with reported improvements in specific mental health conditions.

# Key Features
Data Loading & Preprocessing: Robust handling of survey data, including cleaning and mapping of categorical responses in the 'Music effects' column to numerical values.

Exploratory Data Analysis (EDA): Comprehensive visualizations (histograms, pie charts) to understand listening habits, age distribution, streaming service preferences, and the overall reported impact of music on mental health.

Machine Learning Classification:

Implementation and evaluation of multiple supervised learning models including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVC), and K-Nearest Neighbors (KNN).

Models are trained to classify the impact of music on mental well-being (Improve vs. Worsen/No Effect).

Model Optimization: Hyperparameter tuning (e.g., GridSearchCV for Decision Tree) to enhance model performance.

Genre Insights for Mental Well-being: A custom function to identify and suggest top music genres associated with reported positive mental health effects, particularly for users experiencing specific conditions (e.g., anxiety). This is based on correlations observed in the dataset, providing general trends rather than personalized recommendations.

# Performance & Insights
Classification Accuracy: Achieved competitive accuracy scores across various models, with the Optimized Decision Tree model reaching approximately 76.03% accuracy in predicting music's effect on mental well-being.

Detailed Metrics: Provides Confusion Matrices, Precision, Recall, and F1-Scores for all evaluated classifiers, offering a granular view of model performance.

Genre Correlation: Identifies which genres are most frequently favored by individuals reporting a positive music effect, especially under certain mental health conditions (e.g., "Rock" or "Pop" might show high correlation with improvement for individuals with high anxiety scores).

🛠# Technologies Used
Python: Programming Language

Pandas: Data manipulation and analysis

NumPy: Numerical operations

Matplotlib & Seaborn: Data visualization

Scikit-learn: Machine learning algorithms, model selection, and evaluation
