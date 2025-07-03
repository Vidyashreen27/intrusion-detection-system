# intrusion-detection-system
Intrusion Detection System (IDS)
This project involves building a predictive model to monitor networks and systems for malicious activity, helping prevent unauthorized access—including potential insider threats. The goal is to develop a classifier that can effectively distinguish between "bad connections" (intrusions or attacks) and "good connections" (normal traffic). The model is trained on features extracted from the KDD Cup 1999 dataset provided by DARPA.

Dataset
The KDD Cup 1999 dataset is a widely used benchmark for intrusion detection systems. It contains a mix of normal and attack network traffic and can be downloaded from:
http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

Models and Evaluation
Seven different machine learning algorithms were trained and tested to evaluate their effectiveness in intrusion detection. Each model was assessed based on accuracy and computational time. Among them, the Decision Tree model demonstrated the best performance across both metrics.

Algorithms Used
Gaussian Naive Bayes

Decision Tree

Random Forest

Support Vector Machine (SVM)

Logistic Regression

Gradient Boosting

Artificial Neural Network (ANN)
