# 🧠 Emotional State Prediction System
### ArvyaX Internship Assignment

---

## 📌 About This Project
ArvyaX is a wellness app where users listen to
ambient sounds (ocean, forest, rain, cafe) and
write a journal entry about how they feel.

This ML model reads that journal and predicts
the user's emotional state.

---

## 🎯 What the Model Predicts
- **Emotional State** — focused, calm, restless,
  overwhelmed, mixed, or neutral
- **Intensity** — scale of 1 to 5
- **What to do** — box breathing, deep work, rest, etc.
- **When to do it** — now, tonight, tomorrow morning

---

## 📂 Dataset
- Training data: 99 journal entries with labels
- Test data: 120 entries without labels

---

## 🔧 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Random Forest Classifier

---

## 📊 Result
- Emotional State F1 Score: **94%**
- Uncertain cases flagged for human review: **19**

---

## 🚀 How to Run
```bash
git clone https://github.com/jain-garima-notafk/Arvyax-internship-assignment

pip install pandas scikit-learn numpy
jupyter notebook ArvyaX_Solution.ipynb
```

---

## 👩‍💻 Author
**Garima Jain**
ArvyaX ML Intern | 2025
