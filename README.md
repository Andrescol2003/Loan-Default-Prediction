#  Loan Default Prediction – Deep Learning

##  Overview
This project focuses on predicting student loan defaults using a Deep Learning Neural Network.  
The primary objective is to maximize recall for high-risk borrowers, ensuring the model identifies as many potential defaults as possible.  

---

##  Project Structure
- `notebooks/` → Jupyter notebooks with preprocessing, model building, and evaluation.  
- `data/` → (Not included in repo – link or instructions on where to download dataset).  
- `models/` → Saved model weights (if provided).  
- `requirements.txt` → Python dependencies.  

---

## Methods & Tools
- Data Processing:Pandas, NumPy, Scikit-learn  
- Modeling: TensorFlow, Keras (Neural Network, tuned for recall)  
- Evaluation: Confusion Matrix, Recall Score, F1-Score  
- Handling Imbalance: SMOTE (Synthetic Minority Oversampling)  

---

##  Results
- Neural Network achieved **Recall: 0.85 on default cases.  
- Balanced metrics ensured fewer false negatives, critical for identifying high-risk borrowers.  
