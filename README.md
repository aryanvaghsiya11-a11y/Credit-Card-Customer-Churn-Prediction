Bank Customer Churn Prediction (ANN)
This project implements an Artificial Neural Network (ANN) to predict the likelihood of bank customers churning (leaving the bank). Utilizing customer demographics and financial data, the model provides a binary classification to help financial institutions identify at-risk customers.

🚀 Project Overview
The model follows a rigorous machine learning pipeline to ensure high predictive performance:

Data Preprocessing: Handled missing information and removed non-predictive identifiers like RowNumber and Surname.

Feature Engineering: Applied One-Hot Encoding to categorical variables such as Geography and Gender.

Feature Scaling: Utilized StandardScaler to normalize numerical features, ensuring faster convergence during training.

Deep Learning Architecture: Built a Sequential ANN with a Sigmoid-activated hidden layer and a Sigmoid output layer for binary classification.

Training & Evaluation: Optimized using the Adam optimizer and Binary Cross-Entropy loss over 100 epochs.

📊 Performance
The model achieved an accuracy of approximately 79.75% on the test dataset. The repository includes training history visualizations showing:

Loss Convergence: Tracking training vs. validation loss.

Accuracy Metrics: Monitoring model performance over 100 epochs to prevent overfitting.

🛠️ Technical Stack
Core: Python 3

Deep Learning: TensorFlow, Keras

Data Manipulation: Pandas, NumPy

Preprocessing: Scikit-Learn

Visualization: Matplotlib

📋 Dataset Features
The model analyzes 11 critical features:

Demographics: Age, Gender, Geography (France, Spain, Germany).

Financials: Credit Score, Balance, Estimated Salary, and Number of Products.

Engagement: Tenure, Credit Card ownership, and Active Membership status.
