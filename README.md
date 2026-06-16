**Bio-inspired Algorithms for Loan Default Detection**



**Overview**



This repository contains the implementation and experimental notebooks for the research paper:



**Bio-inspired Algorithms for Loan Default Detection**



The project evaluates multiple hyperparameter optimization techniques for improving loan default prediction models. The study compares traditional search methods with bio-inspired optimization algorithms across several machine learning models.



Dataset



Dataset: UCI Default of Credit Card Clients Dataset

Source: UCI Machine Learning Repository

Target Variable: Loan Default Status



**Machine Learning Models**



Decision Tree Classifier (DTC)

Support Vector Machine (SVM)

LightGBM

XGBoost



**Hyperparameter Optimization Techniques**



Genetic Algorithm (GA)

Particle Swarm Optimization (PSO)

Bayesian Optimization

Grid Search

Random Search



**Data Preprocessing**



The preprocessing pipeline includes:



\* Missing value handling

\* Duplicate removal

\* Feature encoding

\* Feature scaling

\* Feature selection

\* Class imbalance handling using SMOTE and undersampling



**Experimental Results**



The study demonstrates that bio-inspired optimization techniques outperform conventional search methods for hyperparameter tuning.



**Best Performing Configuration**



| Model   | Optimization Method | Accuracy | Recall |

| ------- | ------------------- | -------- | ------ |

| XGBoost | Genetic Algorithm   | 95%      | 93%    |



**Repository Structure**

.

├── All models.ipynb

├── Preprocessing+DTC+gridSearch.ipynb

├── Preprocessing+LightBGM+gridSearch.ipynb

├── Preprocessing+SVM+gridSearch.ipynb

├── Preprocessing+XGBoost+gridSearch.ipynb

└── README.md





**Research Contribution**



This work investigates how evolutionary optimization techniques such as Genetic Algorithms and Particle Swarm Optimization can improve machine learning model performance for credit risk assessment and loan default prediction.



**Authors**



\* Monica Rokade

\* Kaustubh Patil

\* Satyam Kumar

\* Aanvi Bindal

\* Rishabh Zambre

\* Pradnya V. Kulkarni

