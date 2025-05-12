# MSc-Final-Project

**Title: Enhancing Fake Review Detection on Amazon: Machine Learning Techniques for Dynamic Reviewer Behaviour and Group Structure Analysis.**

📘 Project Overview
This MSc dissertation project investigates the detection of fake reviews on Amazon using supervised machine learning techniques. It addresses the limitations of traditional detection methods by incorporating reviewer behavioural dynamics and group structures. The project aims to improve accuracy in identifying deceptive content by leveraging time-based patterns and relational indicators.


🎯 Objectives
- Improve baseline classifiers such as Logistic Regression, SVM, and Random Forest by combining each with deep learning techniques—RNN and GNN—to develop hybrid models for fake review detection.
- Capture temporal patterns in reviewer behaviour and reviewer-reviewer relationships.
- Compare the performance of traditional vs. advanced models on detection accuracy.
- Present a robust evaluation using real-world Amazon review data.


📁 Project Structure
- `data/` – Raw dataset (from Kaggle, anonymised)  
- `data_cleaning.ipynb` – Preprocessing and cleaning process  
- `feature_engineering.ipynb` – Construction of new features (e.g., static/text-based, temporal, behavioral)  
- `feature_selection.ipynb` – Feature importance analysis and selection methods  
- `model_implementation.ipynb` – Implementation, training, and evaluation of ML models 


🔍 Key Features
- Supervised Learning Models: Implemented Logistic Regression, SVM, Random Forest, and deep leaning -RNN, and GNN- architectures.
- Temporal and Relational Features: Engineered features to reflect review timing, frequency, and reviewer group behaviour.
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score.
- Comparative Analysis: Benchmarked traditional and graph-based models for insight into detection performance.


💻 Tools & Technologies
- Python (scikit-learn, pandas, NumPy)
- PyTorch (for GNN/RNN models)
- NetworkX / PyTorch Geometric (for graph construction)
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook


📊 Dataset
Source: Public Amazon review dataset from Kaggle
Fully anonymized and ethically approved. No PII involved.


📈 Results
Overall, the hybrid models incorporating temporal and group structure using RNN and GNN outperformed the traditional models. The hybrid models outperformed baseline classifiers by leveraging user interaction graphs and reviewer time series. Improvements were observed especially in accuracy, confirming the model's ability to capture coordinated spam behaviour.


🔒 License
This project is not open for editing by the public. All rights reserved.
