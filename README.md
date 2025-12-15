# X-Bot-Detection-Using-Machine-Learning
Supervised Machine Learning for Detecting Bot Accounts on X (formerly Twitter)

# Overview
The final version of this project reflects feedback and suggestions from fellow classmate Ben S., which significantly improved the clarity, structure, and business relevance of the analysis. Using a publicly available dataset from Kaggle (https://www.kaggle.com/datasets/davidmartngutirrez/twitter-bots-accounts/versions/1), this repository contains the final project for MGT 661: Artificial Intelligence & Business Analytics, focused on detecting automated bot accounts on X (Twitter) using supervised machine learning techniques. Social Media Bots (SMBs) pose growing risks to brand perception, consumer trust, and the spread of misinformation. 

# Objectives 
Learn about the advatnages of utlizing AI and its tools to solve a business problem. 
Develop machine learning models capable of differentiating human users from bot accounts on X.
Evaluate multiple supervised learning algorithms and compare performance.
Address class imbalance using SMOTE to improve bot‑detection accuracy.
Demonstrate the business risks posed by bots and how ML models can help mitigate them.

# Models Used
Logistic Regression,
Decision Tree Classifier,
Random Forest Classifier, and 
XGBoost Classifier (best overall performer)

# Metrics
- Accuracy
- Precision
- Recall
- F1‑Score
- ROC‑AUC

# Results 
XGBoost achieved the highest ROC‑AUC score of ~87.7%, outperforming all other models.
Applying SMOTE, a balanced precision and recall values improved its ability to detect bots more accurately.
Feature importance analysis showed that Follower count and Statuses count were highly predictive indicators of bot‑like behavior.

# Business Impact
Bots can influence brand reputation, manipulate public sentiment, and distort consumer behavior.
This project demonstrates how machine learning can enhance threat detection for marketing teams, improve brand moniroing, and mitigate misinformation attacks.



