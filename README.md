🔐 Intrusion Detection System using NSL-KDD Dataset
This project is a machine learning-based Intrusion Detection System (IDS) that uses the NSL-KDD dataset to detect and classify network attacks. It demonstrates how supervised learning algorithms can be trained to identify normal and malicious network activity, helping improve cybersecurity.

📁 Files in the Repository
NSL-KDD.ipynb: Jupyter Notebook containing the complete code – data preprocessing, training, evaluation, and visualization.

train_task.csv: The training dataset.

test_task.csv: The testing dataset.

📊 About the Dataset
The NSL-KDD dataset is a refined version of the older KDD Cup 1999 dataset. It contains network traffic records labeled as either normal or one of several types of network attacks (e.g., DoS, Probe, R2L, U2R).

Each record consists of:

41 features (numeric and categorical)

1 label column indicating the class (attack type or normal)

🚀 Project Workflow
Data Loading & Exploration
Load both training and testing datasets, check the shape, column types, and class distributions.

Data Preprocessing

Encode categorical features.

Normalize numerical features.

Remove or handle invalid values.

Prepare data for modeling.

Model Building
Train machine learning models such as:

Random Forest

XGBoost

Decision Tree
Evaluate them using appropriate metrics.

Evaluation & Visualization

Use accuracy, precision, recall, F1-score for evaluation.

Confusion matrix and classification reports to analyze performance.

Results & Insights
Discuss which model performed best and why, and provide potential improvements for real-world implementation.

🧠 Machine Learning Models Used
Random Forest Classifier

XGBoost Classifier

(Add more if you used others like Logistic Regression, etc.)

📈 Model Evaluation Metrics
Accuracy: Overall correctness of the model.

Precision: How many predicted attacks were real.

Recall: How many actual attacks were correctly predicted.

F1 Score: Harmonic mean of precision and recall.

Confusion matrix and class-wise evaluation included.

🛠 Technologies Used
Python

Jupyter Notebook

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost
