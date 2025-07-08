# 🎯 Career Guidance System using Machine Learning

A smart ML-based career recommendation engine that predicts the most suitable career roles for individuals based on their academic skills, personality traits, and interests.

## 🧠 Overview

Choosing the right career is crucial but often confusing for students. This project aims to assist students, particularly from engineering backgrounds, in identifying appropriate career paths by using machine learning classifiers trained on academic, psychological, and behavioral data.

## 📌 Features

- Uses psychological traits and technical skills for career prediction
- Evaluates multiple machine learning classifiers:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
- Trained on a dataset with 9,000+ entries
- Supports expansion to new features and roles
- Includes basic exploratory data analysis (EDA) to understand feature distribution

## 📊 Dataset Description

- File: CareerMapping.csv  
  - 9179 rows × 28 columns  
  - Features include technical skills (Programming Skills, Networking, etc.), soft skills (Communication skills), and personality traits (Openness, Agreeableness, Self-enhancement, etc.)
  - Target variable: Role (e.g., Database Administrator)

- File: CareerMapping1.csv  
  - Subset of key features used for focused training/testing

## 🧪 Algorithms Used

Each of the following classifiers was trained and evaluated using Jupyter notebooks:

- KNN Classifier.ipynb
- Decision Tree Classifer.ipynb
- Random Forest Classifier.ipynb
- SVM Classifier.ipynb
- Naive Bayes Classifier.ipynb

Performance is compared using accuracy, confusion matrix, and classification reports.

- Data_visualization.ipynb — for EDA and plotting insights from the dataset

## 🧱 Project Structure

├── CareerMapping.csv              # Full dataset  
├── CareerMapping1.csv             # Filtered dataset  
├── KNN Classifier.ipynb  
├── Decision Tree Classifer.ipynb  
├── Random Forest Classifier.ipynb  
├── Naive Bayes Classifier.ipynb  
├── SVM Classifier.ipynb  
└── README.md                      # You're here!

## 📈 Example Features Used

- Programming Skills, Project Management, Communication skills  
- Openness, Extraversion, Agreeableness, Conscientousness  
- Behavioral traits: Openness to Change, Self-enhancement, Hedonism

## 🔧 Requirements

- Python ≥ 3.7
- Libraries:
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - seaborn

Install with:
pip install -r requirements.txt

## 🚀 How to Run

1. Clone this repository:
   git clone https://github.com/ShreyaDixit43/Career-Guidance-System-ml.git
   cd Career-Guidance-System-ml

2. Open any of the classifier notebooks:
   jupyter notebook "KNN Classifier.ipynb"

3. Run the cells to see model training, accuracy, and prediction outputs.

## 🤝 Contributing

Pull requests and feedback are welcome! If you'd like to contribute:
- Fork this repo
- Make your changes
- Submit a pull request

## 📜 License

This project is open-source and available under the MIT License.

## 📬 Contact
GitHub: https://github.com/ShreyaDixit43  
Email: shreyadixit098@gmail.com
