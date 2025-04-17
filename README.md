# Intrusion-Detection-System-Using-Machine-Learning
This project builds an Intrusion Detection System (IDS) to classify network traffic as "normal" or "attack" using the KDDTrain+ dataset.

Intrusion Detection System Using Machine Learning
This project presents a robust Intrusion Detection System (IDS) designed to classify network traffic as either "normal" or "attack" by leveraging advanced machine learning techniques. With the increasing complexity of cyber threats, this IDS provides an automated, scalable solution for enhancing network security.

Project Overview
The system utilizes the KDDCup dataset, a widely recognized benchmark in intrusion detection research, for training and evaluation. By implementing efficient preprocessing and dimensionality reduction techniques, the project ensures improved model performance while maintaining computational efficiency.

Features
Data Preprocessing:

Simplified target variables into binary categories: normal and attack.

Applied one-hot encoding for categorical features.

Standardized numerical features using RobustScaler to address outliers.

Dimensionality Reduction:

Utilized Principal Component Analysis (PCA) to reduce features to 20 components while retaining key variance.

Machine Learning Models:

Logistic Regression: Effective for binary classification tasks.

Gaussian Naive Bayes: A probabilistic model with an independence assumption.

Decision Tree Classifier: Optimized with controlled depth to prevent overfitting.

Evaluation Metrics:

Assessed model performance using accuracy, precision, recall, and F1-score for a comprehensive evaluation.

Key Tools & Technologies
Languages: Python

Libraries: NumPy, Pandas, Matplotlib, Scikit-learn

Techniques: Data preprocessing, PCA, model training, and evaluation

Results
The implemented models demonstrated high accuracy and effective classification of network traffic. The project serves as a practical example of applying machine learning to solve cybersecurity challenges, offering insights for real-world applications.
