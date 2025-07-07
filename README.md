# 🧠 Toxic Comment Detection

This project uses Natural Language Processing (NLP) and Machine Learning techniques to detect **toxic comments** in textual data. It was developed as a mini project for academic purposes using Python in a Jupyter notebook.

---

## 📌 Objective

To classify whether a given comment is **toxic** or **non-toxic** using machine learning classifiers based on comment text features.

---

## 🧰 Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas, NumPy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Seaborn & Matplotlib (for visualization)

---

## 📂 File Structure

| File                            | Description                                                                      |
|---------------------------------|----------------------------------------------------------------------------------|
| `Toxic_Comment_Detection.ipynb` | Main notebook containing preprocessing, model building, training, and evaluation |
| `README.md`                     | Project documentation                                                            |

---

## 🔍 Key Components

- ✅ **Data Preprocessing**
  - Text cleaning (lowercase, punctuation removal)
  - Stopword removal
  - Tokenization
  - Lemmatization using NLTK

- ✅ **Vectorization**
  - TF-IDF (Term Frequency-Inverse Document Frequency)

- ✅ **Model Training**
  - Logistic Regression
  - Naive Bayes

- ✅ **Evaluation**
  - Confusion matrix
  - Accuracy, Precision, Recall, F1-score

---

## 📊 Dataset

The project uses a sample CSV dataset (`train.csv`) with the following columns:
- `comment_text`: The actual text of the comment
- `toxic`: Binary label (1 = toxic, 0 = non-toxic)

> Dataset format aligns with the [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/HarshPeke-2004/Toxic-comment-detection.git
   cd Toxic-comment-detection
