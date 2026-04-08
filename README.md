#  Network Intrusion Detection System using Machine Learning

##  Project Overview

This project implements a **Machine Learning-based Network Intrusion Detection System (NIDS)** designed to detect malicious network traffic and classify it as **normal or attack** traffic.  

The system uses the **NSL-KDD dataset**, a widely used benchmark dataset in cybersecurity research, and applies multiple machine learning algorithms along with ensemble learning techniques to improve detection accuracy.

---

##  Objectives

- Detect malicious network traffic using supervised machine learning models  
- Improve model performance using preprocessing and feature engineering  
- Handle imbalanced datasets using SMOTE  
- Compare multiple models and build an ensemble model  
- Evaluate model performance using classification metrics  

---

##  Dataset

**Dataset Used:** NSL-KDD Dataset  

The dataset contains network traffic records labeled as:

- Normal traffic  
- Denial of Service (DoS) attacks  
- Probe attacks  
- Remote to Local (R2L) attacks  
- User to Root (U2R) attacks  

The dataset includes both **numerical** and **categorical features**, requiring preprocessing before training machine learning models.

---

##  Methodology

The project follows a complete machine learning pipeline:

### 1. Data Preprocessing

- Label Encoding of categorical features  
- Feature Scaling using StandardScaler  
- Handling class imbalance using **SMOTE**  
- Feature Selection using **SelectKBest**

These steps improve model accuracy and efficiency.

---

### 2. Machine Learning Models Used

The following models were implemented and evaluated:

- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **XGBoost Classifier**

---

### 3️. Ensemble Learning

A **Weighted Soft Voting Ensemble Model** was created by combining:

- SVM  
- Random Forest  
- XGBoost  

This improves overall prediction performance and reduces individual model bias.

---

##  Evaluation Metrics

The models were evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  
- Classification Report  

These metrics help assess how well the system detects malicious traffic.

---

##  Technologies Used

**Programming Language:**
- Python

**Libraries & Tools:**
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- XGBoost  
- Imbalanced-learn (SMOTE)

---

##  Project Structure

```
network-intrusion-detection-ml/
│
├── intrusion_detection.ipynb
├── README.md
├── requirements.txt
├── dataset/
│   └── (NSL-KDD dataset files)
└── results/
    └── (plots, confusion matrix, outputs)
```



---

##  Key Features

- Data preprocessing pipeline  
- Feature selection using SelectKBest  
- SMOTE for handling imbalanced data  
- Multiple ML models implementation  
- Ensemble learning model  
- Performance evaluation using classification metrics  

---

##  Applications

This system can be applied in:

- Network Security Systems  
- Cybersecurity Monitoring  
- Intrusion Detection Systems  
- Security Analytics  

---

##  Author

**A. Leela Subhash**  

- Email: alsubhash01@gmail.com  
- GitHub: https://github.com/Subhash-13  

---

##  Future Improvements

- Hyperparameter tuning for better performance  
- Real-time intrusion detection implementation  
- Deployment using web frameworks  
- Integration with real network traffic data  
