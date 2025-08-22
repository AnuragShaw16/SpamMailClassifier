📧 Email Spam Classifier
Overview

Spam detection primarily relies on email filtering, which separates incoming messages into spam and legitimate mail. By leveraging machine learning, models can be trained on text content and metadata to automatically identify and block spam.

🔹 Project Description

The entire implementation is done in Python.

Dataset is sourced from Kaggle: SMS Spam Collection Dataset
.

Key libraries used: pandas, re, nltk, sklearn, seaborn, matplotlib, tqdm, and time.

Workflow includes: Data Cleaning, NLP processing, Model Training, and Performance Evaluation.

Logistic Regression was chosen as the classification model due to its high accuracy on text-based spam detection.

Performance is evaluated with a confusion matrix heatmap and a detailed classification report.

🔹 Techniques Applied in Spam Detection

Email Filtering: Core technique for separating spam from genuine emails using rule-based and machine learning approaches.

Natural Language Processing (NLP): Enables machines to interpret email text by extracting useful features such as subject lines, message body, and metadata.

Text Classification: A supervised learning approach where emails are labeled spam or not based on word usage, structure, and style.

Feature Engineering: Selecting key attributes like sender details, keyword frequency, and email length to improve classification accuracy.

Supervised Learning: Training on labeled datasets so the model can predict outcomes for unseen data.

Unsupervised Learning: Identifying hidden structures in data (e.g., clustering similar spam types) without labeled examples.

Deep Learning: Using neural networks with multiple layers to capture complex patterns in spam content.

Neural Networks: Inspired by the human brain, these models can learn meaningful representations and classify emails effectively.