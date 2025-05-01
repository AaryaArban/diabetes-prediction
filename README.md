# **🧬 Diabetes Prediction using Machine Learning**
This project applies machine learning techniques to predict the likelihood of diabetes based on medical attributes. By using classification algorithms such as Logistic Regression, Decision Tree, and Gaussian Naive Bayes, the project aims to determine the most accurate model through ROC-AUC evaluation and hyperparameter tuning.

🎯 Project Objective

To build a predictive model that accurately classifies individuals as diabetic or non-diabetic using clinical features from a dataset. The project follows a complete ML pipeline from data preprocessing to model optimization.

⚙️ Tools & Technologies

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

Classification Algorithms:

Logistic Regression

Decision Tree

Gaussian Naive Bayes

🗂️ Project Workflow

1. Data Cleaning

Handled missing values by replacing them with appropriate statistical measures.

Removed or treated anomalies to ensure data integrity.

2. Exploratory Data Analysis (EDA)

Visualized feature distributions, correlations, and class balance using Seaborn and Matplotlib.

Understood patterns in the dataset that influence diabetes diagnosis.

3. Feature Engineering

Performed feature scaling and normalization to standardize the dataset.

Ensured compatibility across different algorithms by preparing the input data appropriately.

4. Model Building

Trained and tested the following classifiers:

Logistic Regression

Decision Tree Classifier

Gaussian Naive Bayes

5. Model Evaluation

Evaluated performance using:

Accuracy score

Confusion Matrix

ROC Curve and AUC (Area Under the Curve)

Compared ROC-AUC plots of all models to select the best baseline classifier.

6. Hyperparameter Tuning

Applied GridSearchCV for optimal parameter selection.

Retrained the models with best parameters and re-evaluated using ROC-AUC curve.

Achieved improved performance after tuning.

📈 Results

The best-performing model was selected based on ROC-AUC score post tuning.

📊 Visualizations

🔹 ROC Curves (Before and After Tuning)

🔹 Feature Distributions

🔹 Heatmaps of Correlation

🔹 Confusion Matrices



