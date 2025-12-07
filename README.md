
---

## 📝 **Project Description**

The goal of this project is to classify resumes into appropriate job roles using machine learning. It involves:

- Text extraction from resumes  
- Data cleaning & preprocessing  
- Feature extraction using TF-IDF  
- Model training & evaluation  
- Saving ML models for deployment  
- Testing predictions on real resume samples  

This helps recruiters automatically categorize resumes and speed up the screening process.

---

## 🔧 **Technologies Used**

- **Python**
- **NLP (Natural Language Processing)**
- **Scikit-learn**
- **TF-IDF Vectorization**
- **KNN Classifier**
- **Pandas / NumPy**
- **Pickle (Model Saving)**  
- **Jupyter Notebook**

---

## 📊 **Machine Learning Workflow**

1. Load and merge resume datasets  
2. Clean and preprocess text  
3. Label encode the target categories  
4. Convert text to numerical features (TF-IDF)  
5. Train KNN classifier  
6. Save trained model and vectorizer  
   - `knn.pkl`
   - `tfidf.pkl`
   - `le.pkl`
7. Predict on new resumes in deployment notebook  

---

## 🚀 **How to Run the Project**

### **1. Install the required packages**
Open Jupyter Notebook and run:

```python
!pip install -r requirements.txt
