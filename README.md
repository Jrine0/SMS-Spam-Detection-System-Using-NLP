# SMS-Spam-Detection-System-Using-NLP
SMS Spam Detection is a machine learning model that takes an SMS as input and predicts whether the message is a spam or not spam message. The model is built using Python and deployed on the web using Streamlit.

This project, "SMS Spam Detection Using Machine Learning," addresses the growing need for efficient and automated spam message classification to combat unsolicited communications. Traditional methods for spam detection are often manual and time-consuming, leading to inefficiencies in real-time identification. The primary objective of this project is to design and deploy a machine-learning model capable of accurately predicting whether an SMS is spam or not, thereby enhancing user convenience and security.

The methodology involves several stages: data collection, cleaning and preprocessing, exploratory data analysis, model building and selection, and web deployment. The dataset, comprising over 5,500 labelled SMS messages, was sourced from Kaggle. Data preprocessing steps included handling null and duplicate values, tokenization, removal of special characters and stop words, stemming, and converting text to lowercase for standardization. Exploratory Data Analysis (EDA) provided insights into message structure through character, word, and sentence counts, alongside visualizations such as word clouds, heatmaps, and bar charts.

For model building, various classifiers were evaluated, including Naive Bayes, random forest, logistic regression, decision trees, KNN, ExtraTreesClassifier, and SVC. The model with the best performance, achieving a precision of 100%, was selected for deployment.

Technology Used
Python
Scikit-learn
Pandas
NumPy
Streamlit

Features
Data collection
Data cleaning and preprocessing
Exploratory Data Analysis
Model building and selection
Web deployment using Streamlit

The system's deployment was achieved using Streamlit, featuring a simple web interface where users can input SMS messages and receive predictions on whether they are spam or not in real-time. This user-friendly approach ensures accessibility and practicality for diverse users.

Key results highlight the model's exceptional performance in spam detection, validated by precision and other metrics. In conclusion, the project successfully delivers a robust, web-accessible spam detection system. Future enhancements could include integrating multi-language support, adapting advanced NLP techniques, or addressing evolving spam patterns to maintain effectiveness.
