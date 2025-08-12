# 📄 Task 1: Extractive Text Summarization

This project is a **Natural Language Processing (NLP)** based **Extractive Text Summarization Tool** that automatically selects and extracts the most relevant sentences from a given paragraph. It uses **TF-IDF scoring with stopword removal** and **cosine similarity** to ensure the summary remains concise while preserving the original meaning. The generated summaries are also evaluated using **ROUGE metrics** to measure their quality against reference summaries.

---

## 🚀 Tech Stack

- 🧠 **NLTK** – Sentence tokenization and stopword removal  
- 📊 **Scikit-learn** – TF-IDF vectorization & similarity calculations  
- 🔢 **NumPy** – Mathematical operations for scoring  
- 📦 **Joblib** – For saving vectorizer and matrices  
- 📈 **rouge-score** – To evaluate summary quality  

---

## ✨ Features

✅ Extracts the most important sentences from any text  
✅ Removes stopwords to improve vectorization quality  
✅ Uses TF-IDF for intelligent ranking of sentences  
✅ Adjustable summary length for flexibility  
✅ Saves vectorizer and matrices for reproducibility  
✅ Evaluates summaries using ROUGE metrics  
✅ Works offline without external API calls  
✅ Simple, clean, and beginner-friendly implementation  

---

## 📂 Project Structure

```
Task1_TextSummarizer/
│
├── summarizer.ipynb # Main Jupyter Notebook implementation
├── requirements.txt # Dependencies list
├── vectorizer.pkl # Saved TF-IDF vectorizer file
├── tfidf_matrix.pkl # Saved TF-IDF matrix file
└── README.md # Project documentation
```

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/NullClassInternship_Task1_TextSummarizer.git
cd NullClassInternship_Task1_TextSummarizer
```
### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate     # Windows
# or
source venv/bin/activate  # macOS/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

- Open summarizer.ipynb in Jupyter Notebook or VS Code
- Run all cells to see the generated summary for your input text and ROUGE evaluation

---

## 💬 Sample Interactions

### Input:

Machine learning is a field of computer science that gives computers the ability to learn without being explicitly programmed.
It has become a key technique for solving a wide range of problems in science and industry.
Applications of machine learning are everywhere: in recommendation systems, spam filtering, image recognition, self-driving cars, and more.
Instead of writing code to solve a problem, you feed data into a generic algorithm, and it builds its own logic based on that data.
This has opened up entirely new possibilities in automation and artificial intelligence.

### Output:

It has become a key technique for solving a wide range of problems in science and industry.
Applications of machine learning are everywhere: in recommendation systems, spam filtering, image recognition, self-driving cars, and more.

---

## 📦 requirements.txt

```
nltk
scikit-learn
numpy
rouge-score
joblib
```

---

## 📌 Notes

- You can adjust the number of sentences in the summary by modifying the selection logic in the notebook.
- Works best with clear, well-structured text.
- No internet connection is required after installation.
- The project includes ROUGE evaluation to assess summary quality against reference summaries.
- Saved model files (vectorizer.pkl and tfidf_matrix.pkl) are included for reproducibility and faster loading.

---

## 👨‍💻 Developed By

Pratham Modi
📅 July 2025