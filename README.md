Student Performance Prediction
This project uses Ensemble Learning to predict student academic outcomes (Pass/Fail). By combining multiple machine learning models through a Voting Classifier, the system achieves higher accuracy and reliability than using a single model alone.

🚀 Overview
Predicting student performance helps educators identify students who may need additional support. This project analyzes academic, demographic, and psychological factors to provide a final prediction.

Key Features
Comprehensive Preprocessing: Handles categorical data encoding and numerical feature scaling.

Multiple Model Comparison: Evaluates Logistic Regression, Decision Trees, SVM, and KNN.

Ensemble Strategy: Implements Hard and Soft Voting to aggregate predictions from all models.

Real-world Prediction: Includes an inference script to test new student data.

📊 Dataset Features
The model is trained on 10 key features:

Academic: Previous Scores, Study Hours, Attendance (%).

Demographic: Age, Gender, Parental Education.

Environment: Internet Access, Extra Classes.

Personal: Stress Levels.

🛠️ Models Implemented
The project compares and combines the following algorithms:

Logistic Regression (Baseline)

Decision Tree

Random Forest (Bagging Ensemble)

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Voting Classifier (The final ensemble model)

⚙️ How It Works
The project follows a standard machine learning pipeline:

Data Loading: Reads student_performance.csv.

Encoding: Uses LabelEncoder to convert text data into numerical values.

Scaling: Uses StandardScaler to normalize numerical ranges.

Training: Splits data into training and testing sets.

Voting: The individual models "vote" on the outcome. Soft Voting is used to average the probabilities for the final result.

💻 Tech Stack
Language: Python

Libraries: * pandas & numpy (Data manipulation)

scikit-learn (Machine learning & preprocessing)

matplotlib (Visualization)

📈 Results
The final prediction is output as:

PASS: Likely to succeed based on current metrics.

FAIL: May require academic intervention.
