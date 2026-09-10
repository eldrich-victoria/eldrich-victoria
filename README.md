# **Hi, I'm Eldrich Victoria**

**Data Scientist | Machine Learning Engineer | NLP | Deep Learning | Python**

I build end-to-end machine learning systems, from data preparation and feature engineering to model evaluation and application development.

I recently completed an 11-month Data Science internship at Fourise Software Solutions, where I worked on data collection, web scraping, dataset preparation, exploratory analysis, machine-learning experimentation, model evaluation, automation, backend scripting, and application testing.

My independent projects focus on machine learning, NLP, anomaly detection, recommendation systems, and ML application development. I prefer projects where the implementation can be evaluated through experiments, measurable results, and clear engineering trade-offs.

## **Technical Skills**

**Programming & Data Science**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)](https://numpy.org/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)](https://www.mysql.com/)

**Machine Learning & Deep Learning**

[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)](https://xgboost.readthedocs.io/)
[![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=for-the-badge)](https://lightgbm.readthedocs.io/)
[![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge\&logoColor=black)](https://catboost.ai/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge\&logo=keras\&logoColor=white)](https://keras.io/)

**NLP & Computer Vision**

[![TF-IDF](https://img.shields.io/badge/TF--IDF-4B8BBE?style=for-the-badge)](https://scikit-learn.org/stable/modules/feature_extraction.html)
[![BERT](https://img.shields.io/badge/BERT-FF6F00?style=for-the-badge)](https://huggingface.co/docs/transformers/)
[![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-FFD21E?style=for-the-badge)](https://www.sbert.net/)
[![LIME](https://img.shields.io/badge/LIME-6A1B9A?style=for-the-badge)](https://github.com/marcotcr/lime)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge\&logo=opencv\&logoColor=white)](https://opencv.org/)
[![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://python-pillow.org/)
[![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge)](https://docs.ultralytics.com/)

**Backend & Application Development**

[![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge\&logo=flask\&logoColor=white)](https://flask.palletsprojects.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge\&logo=streamlit\&logoColor=white)](https://streamlit.io/)
[![REST API](https://img.shields.io/badge/REST%20API-02569B?style=for-the-badge)](https://www.ibm.com/topics/rest-apis)

**Data Acquisition, Databases & Development Tools**

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)](https://www.mysql.com/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge\&logo=sqlite\&logoColor=white)](https://www.sqlite.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)](https://jupyter.org/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/)
[![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge\&logo=pytest\&logoColor=white)](https://pytest.org/)
[![unittest](https://img.shields.io/badge/unittest-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://docs.python.org/3/library/unittest.html)


## **Selected Projects**

## Adversa — Adversarial Toxic Language Auditor

A local retrieval-based NLP pipeline for detecting toxic language that has been deliberately obfuscated through leetspeak, character repetition, spacing, Unicode homoglyphs, symbol substitutions, and toxic emoji combinations.

- 99.1% in-distribution accuracy
- 100.0% held-out accuracy
- 0.994 in-distribution F1
- 1.000 held-out F1
- 53 passing unit and integration tests
- Uses sentence-transformers, cosine similarity, rule-based heuristics, and a deterministic scoring pipeline

[View repository](https://github.com/eldrich-victoria/Adversa)

## FraudLens — Financial Fraud Detection

An end-to-end machine-learning risk-scoring system for transaction fraud detection under severe class imbalance and high-dimensional transaction data.

- 458 engineered features
- LightGBM achieved 0.9437 OOF ROC-AUC and 0.7409 PR-AUC
- 0.7066 F1 with 0.8382 precision and 0.6107 recall
- Approximately 46% RAM reduction through numeric downcasting
- Includes model comparison, serialized preprocessing/model artifacts, batch prediction, and adjustable fraud-risk thresholds

[View repository](https://github.com/eldrich-victoria/FraudLens)

## Toxic Comment Detection System

An NLP platform combining classical machine-learning baselines with BERT-based classification, adversarial text normalization, explainability, REST APIs, and application interfaces.

- BERT accuracy: 94.80%
- Toxic F1: 70.43%
- Evaluated on a 389,820-sample Version 2 dataset
- 100,000 samples used for BERT fine-tuning
- Includes LIME explanations, FastAPI inference, Streamlit interface, SQLite persistence, and automated testing

[View repository](https://github.com/eldrich-victoria/Toxic-Comment-Detection-System)

## NetSentinel — Network Anomaly Detection

An unsupervised network anomaly detection system using the UNSW-NB15 dataset and multiple anomaly-detection approaches.

- Compares Local Outlier Factor, Isolation Forest, One-Class SVM, and a PyTorch Autoencoder
- LOF achieved 80.64% accuracy and 80.14% F1
- ROC-AUC of 0.8898 for LOF
- Includes severity-based alerts, evaluation reports, model artifacts, and a Streamlit dashboard

[View repository](https://github.com/eldrich-victoria/NetSentinel)

## Flavour Finder — Restaurant Recommendation System

A content-based recommendation system using cuisine, locality, and budget information to retrieve relevant restaurant recommendations.

- 51,717 restaurants processed
- Uses CountVectorizer and cosine similarity
- Reports sub-10 ms similarity computation
- Reduced similarity-memory requirements from approximately 4.2 GB to 20 MB

[View repository](https://github.com/eldrich-victoria/Flavour-Finder)

## **Experience**

**Data Science Intern — Fourise Software Solutions Pvt. Ltd.**

September 2025 – August 2026

Worked across data research, data collection, web scraping, preprocessing, document extraction, exploratory analysis, machine-learning experimentation, model evaluation, automation, backend scripting, application testing, and Git/GitHub-based development.

## **Education**

**B.Tech in Computer Science Engineering (Data Science)**  
D. Y. Patil Agriculture & Technical University  
2026

## **Connect**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/eldrich-victoria/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/eldrich-victoria)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:victoriaeldrich2004@gmail.com)
