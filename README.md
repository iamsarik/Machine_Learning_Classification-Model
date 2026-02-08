📌 Project Overview

This project demonstrates the development and evaluation of a binary classification machine learning model, with a strong focus on handling class imbalance. The model is trained and tested on both unbalanced data and balanced data using SMOTE, allowing a clear comparison of performance across different evaluation metrics.

The implementation is provided in a Jupyter Notebook and follows standard machine learning practices including preprocessing, model training, evaluation, and performance comparison.


🧪 Techniques Used

Data preprocessing and feature scaling

Handling class imbalance using SMOTE (Synthetic Minority Oversampling Technique)

Model training and testing

Performance evaluation using multiple metrics


📊 Model Performance Comparison
Dataset Type	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Unbalanced Data	0.9708	1.0000	0.9219	0.9594	0.9957
Balanced Data (SMOTE)	0.9825	1.0000	0.9531	0.9760	0.9978
<img width="870" height="405" alt="Screenshot 2026-02-08 193406" src="https://github.com/user-attachments/assets/00f6fa43-8356-41ce-877c-dab6a2161194" />
<img width="490" height="420" alt="Screenshot 2026-02-08 193509" src="https://github.com/user-attachments/assets/3b5f00df-256d-4922-8b25-5d8c02bf6d0b" />



🔍 Key Observations

Precision remains perfect (1.0) in both cases, indicating zero false positives.

Recall improves after applying SMOTE, meaning the model detects more minority-class instances.

F1-score increases with balanced data, showing a better trade-off between precision and recall.

ROC-AUC improves slightly, confirming stronger overall classification capability after balancing.

SMOTE helps mitigate class imbalance without sacrificing model stability.


🛠 Tools & Libraries

Python

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)


📁 Repository Structure
├── ML_Model1.ipynb
├── README.md


🎯 Conclusion

Balancing the dataset using SMOTE leads to measurable improvements in recall, F1-score, and ROC-AUC, making the model more reliable for real-world scenarios where minority-class detection is critical.

This project serves as a practical reference for understanding the impact of class imbalance and the effectiveness of oversampling techniques in machine learning classification tasks.
