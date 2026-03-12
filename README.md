# Small-Project_IDS-ML
# Machine Learning for Network Intrusion Detection

This project compares several machine learning models on two intrusion detection datasets: the older KDD Cup 1999 and the modern UNSW-NB15. The goal is to understand how different algorithms behave under very different data conditions.

## Summary
- Custom preprocessing for each dataset  
- Six supervised models: LR, KNN, SVM, Decision Tree, Random Forest, ANN  
- Evaluation with accuracy, precision, recall, F1, ROC-AUC, log-loss 
- Convergence analysis to study how performance scales with training-set size
- K-Means clustering with PCA for unsupervised analysis  

## Datasets
**KDD Cup 1999** - simple and highly separable; all models perform extremely well.  
**UNSW-NB15** - more realistic and complex; requires winsorization and one-hot encoding.