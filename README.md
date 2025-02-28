AI-Powered Resume Classification System 🚀

Overview

This project is a machine learning-based resume classification system that predicts the job category of a given resume using Natural Language Processing (NLP) and machine learning algorithms. It utilizes TF-IDF vectorization for text representation and Support Vector Machine (SVM) for classification.

Features

✅ Preprocesses resumes (removes stop words, punctuation, URLs, etc.)✅ Transforms text using TF-IDF✅ Classifies resumes into predefined job categories✅ Uses SVM (svc_model) and KNN (knn) classifiers✅ Trained on labeled resume data✅ Easily extendable to other models (e.g., Naïve Bayes, Random Forest, etc.)

Technologies Used

Python 🐍

Scikit-learn (Machine Learning)

NLTK (Text Preprocessing)

Regex (Text Cleaning)

Pickle (Model Saving & Loading)

How It Works?

1️⃣ Preprocessing → Cleans resume text using cleanResume().2️⃣ Vectorization → Converts text into numerical features using TF-IDF.3️⃣ Classification → Predicts job category using SVM (One-vs-Rest).4️⃣ Prediction → Returns the most relevant job category for the resume.
