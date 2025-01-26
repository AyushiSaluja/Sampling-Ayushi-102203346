
### README FILE

#### **Overview**  
Credit card fraud detection is a critical task where imbalanced datasets can hinder the performance of machine learning models. This project involves:  
1. Balancing the dataset using the Synthetic Minority Oversampling Technique (SMOTE).  
2. Creating five samples of different sizes using various sampling techniques.  
3. Training five machine learning models on these samples.  
4. Comparing model performance and identifying the best sampling technique for each model.

---

#### **Dataset**  
The dataset used is `Creditcard_data.csv`, containing:  
1. **Features (V1 to V28):** Principal components of transaction data.  
2. **Time:** Seconds elapsed between transactions.  
3. **Amount:** Transaction amount.  
4. **Class:** Fraud label (0 for legitimate, 1 for fraud).  

**Class Imbalance:**  
The dataset is highly imbalanced with:  
- **Class 0:** 98.83% of transactions (legitimate).  
- **Class 1:** 1.17% of transactions (fraudulent).  

---

#### **Sampling Techniques**  
1. **Random Sampling:** Randomly selects a subset of data.  
2. **Stratified Sampling:** Ensures class proportions are maintained.  
3. **Systematic Sampling:** Selects every nth sample.  
4. **Cluster Sampling:** Divides the dataset into clusters and selects entire clusters.  
5. **Oversampling:** Increases minority class instances further.

---

#### **Machine Learning Models**  
1. Logistic Regression  
2. Decision Tree  
3. Random Forest  
4. Support Vector Machine (SVM)  
5. Gradient Boosting  

---

#### **Observations**  
Based on the results:  
1. **Logistic Regression:** Performed best with **Sample 5** (Random Sampling or Oversampling).  
2. **Decision Tree:** Achieved the highest accuracy with **Sample 5** (Oversampling).  
3. **Random Forest:** Gave the best result with **Sample 4 and Sample 5** (Oversampling).  
4. **SVM:** Performed consistently but achieved its best result with **Sample 5** (Oversampling).  
5. **Gradient Boosting:** Showed peak performance with **Sample 5** (Oversampling).

---
