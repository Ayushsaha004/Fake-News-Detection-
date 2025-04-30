# Fake-News-Detection-

This is a machine learning project I worked on to detect fake news using NLP techniques. I used the LIAR dataset and applied data preprocessing, TF-IDF vectorization, and trained a classifier to identify whether a news statement is real or fake.

I explored and customized this project by learning from an open-source repository and adapting the code to better understand the complete machine learning pipeline — from data loading to deployment using Flask.

📁 Project Overview
This project includes:

Preprocessing of raw text data (cleaning, lemmatization, stopword removal)
Feature extraction using TF-IDF Vectorizer
Model training using Logistic Regression (can be changed)
Saving the model using joblib
A simple Flask app for real-time prediction

📊 Dataset
The project uses the LIAR dataset, which includes labeled short statements (e.g. from politicians) that are classified into multiple truthfulness categories. For simplicity, I converted them into binary labels (fake or real).

Dataset source: LIAR Dataset (https://paperswithcode.com/dataset/liar)

🔧 How to Run
Clone the repository:

git clone https://github.com/YOUR_USERNAME/fake_news_detection.git
cd fake_news_detection
Install dependencies:

pip install -r requirements.txt
python app.py


🧠 What I Learned
How to work with real-world text datasets

Applying NLP preprocessing techniques

Building a classification model using scikit-learn

Saving and loading models for deployment

Creating a Flask web application for ML model integration

🙏 Acknowledgements
This project is based on the structure of an open-source repository I studied:

During this project, I referred to several academic papers and articles to understand techniques for fake news detection, text classification, and NLP feature extraction:

[1]Wang, William Y. (2017). "Liar, Liar Pants on Fire: A New Benchmark Dataset for Fake News Detection."
This paper introduced the LIAR dataset and baseline models.
[2]Ruchansky et al. (2017). "CSI: A Hybrid Deep Model for Fake News Detection."
Helped me understand how combining user behavior and content improves detection accuracy.
[3]Zhou & Zafarani (2020). "Fake News Detection: A Survey."
Gave me a broader overview of state-of-the-art approaches in fake news detection.
[4]Shu et al. (2019). "Beyond News Contents: The Role of Social Context for Fake News Detection."
This emphasized the importance of user metadata and propagation, even though I focused on content only.
