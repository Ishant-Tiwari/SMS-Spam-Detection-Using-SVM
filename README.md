# SMS-Spam-Detection-Using-SVM

# 📩 SMS Spam Detection Using SVM

This project uses a Support Vector Machine (SVM) to classify SMS / messages as **Spam** or **Not Spam**. It includes a simple **Gradio GUI** for real-time testing.

---

## 🧠 Features

- Text preprocessing with NLTK
- TF-IDF vectorization
- SVM classification
- Gradio interface for live input and prediction

---

## 📁 Files

- `spam.csv` – Dataset
- `finalized_model.sav` – Trained SVM model
- `tfidf_vectorizer.pkl` – TF-IDF vectorizer
- `app.ipynb` – Google Colab notebook

---

## ▶️ Run in Colab

```python
interface.launch(share=True)
