
# 🧠 Smart Diseases Recommendations System 💉

Welcome to your AI-powered medical companion!  
This project leverages machine learning to diagnose diseases based on user symptoms—fast, accurate, and reliable.

---

## 🚑 Overview

We’ve all Googled symptoms before.  
But instead of spiraling into worst-case scenarios, why not use data science to **predict diseases more intelligently**?

> This project builds a **Smart Disease Prediction System** using patient-reported symptoms and a **Random Forest Classifier**—all wrapped in a user-friendly **Streamlit web interface**.

---

## 📂 Project Structure

| File / Folder | Description |
|---------------|-------------|
| `Smart_Diseases_Recommendations_System.ipynb` | Jupyter Notebook containing the complete implementation |
| `Random_forest_model.pkl` | Trained machine learning model for disease prediction |
| `medical_data.csv` | Dataset used for training (symptoms vs diseases) |
| `app.py` *(optional)* | Streamlit application script |
| `README.md` | You’re reading it! |

---

## 🎯 Objectives

- Build a robust machine learning model using Random Forest
- Classify diseases based on multi-symptom inputs
- Ensure model interpretability and high accuracy
- Create a clean and interactive web app using Streamlit

---

## 📊 Dataset Summary

The dataset includes:

- **Symptom Features**: Multiple binary columns indicating presence/absence
- **Target Variable**: Disease/condition diagnosed
- **Balanced**: Handled class imbalance using class weights

---

## 🤖 Model Performance

- **Model Used**: Random Forest Classifier 🌲
- **Accuracy**: ~98%  
- **Metrics Used**:
  - Confusion Matrix
  - Classification Report
  - Accuracy Score


---

## 🧪 How It Works

```python
# Example of making a prediction
input_symptoms = ['headache', 'fatigue', 'fever']
encoded_input = encode_symptoms(input_symptoms)
prediction = model.predict([encoded_input])
print("Predicted Disease:", prediction[0])
```

---

## 📈 Visuals & Evaluation

- Heatmaps of confusion matrix  
- Class-wise precision, recall, and F1 scores  
- Disease frequency and symptom correlation plots

![Confusion Matrix](https://github.com/user-attachments/assets/f908b417-b431-4595-af56-8d53acf992f1)

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)
- Streamlit (for UI)
- Matplotlib & Seaborn (for visualization)
- Pickle (for model serialization)

---

## 🧠 Key Insights

- 🌡️ Fever, fatigue, and cough are strong indicators for many conditions
- 🧬 Symptom combinations play a crucial role in disease prediction
- 💯 Random Forest consistently outperforms simpler classifiers

---

## 🚀 Getting Started

1. Clone the repository  
2. Install required packages:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:  
   ```bash
   streamlit run app.py
   ```

---

## 📎 Author

Made with ❤️ by **Manthan Jadav**  
Passionate about AI in healthcare, automation, and problem-solving with code.

---

## 📢 License

Free to use, improve, or deploy. Just remember:
> Don’t diagnose yourself with a fatal disease just because the model said so 😉—always consult a real doctor.

