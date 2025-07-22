🩺 Disease Prediction Using Symptoms

This machine learning project predicts the top 5 possible diseases based on the symptoms provided by the user. It also returns a short description of each disease and suggests precautionary measures.

---

🔍 Project Goals

- Predict potential diseases from user-given symptoms  
- Provide informative descriptions and precaution tips  
- Help in early disease detection and awareness  

---

📂 Dataset

The model is trained using a combination of medical datasets:

- `dataset.csv`: Mapping of symptoms to diseases  
- `Symptom-severity.csv`: Severity level for each symptom  
- `symptom_Description.csv`: Disease-wise short descriptions  
- `symptom_precaution.csv`: Disease-wise precautionary steps  

---

🚀 Main Steps

- Load and clean datasets  
- Preprocess symptom columns and remove nulls  
- Create binary features for symptoms  
- Label encode diseases  
- Train machine learning model (Random Forest)  
- Save model using Pickle  
- Build prediction function that returns top 5 diseases with:
  - Prediction probability  
  - Description  
  - 4 Precautionary tips  

---

📊 Output

```python
# Sample Input
predict_disease(['headache', 'vomiting', 'chills'])
