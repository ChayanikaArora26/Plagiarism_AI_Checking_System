# Plagiarism_AI_Checking_System


This project trains a simple machine learning model to classify whether a piece of text is **AI-generated** or **Human-written** using the [`shahxeebhassan/human_vs_ai_sentences`](https://huggingface.co/datasets/shahxeebhassan/human_vs_ai_sentences) dataset from Hugging Face.  

The model uses **TF-IDF vectorization** and a **Logistic Regression classifier** from scikit-learn.  

---

## 🚀 Features
- Loads dataset from Hugging Face.
- Splits data into training and testing sets.
- Uses **TF-IDF** for feature extraction.
- Trains a **Logistic Regression** model.
- Provides evaluation metrics (precision, recall, F1-score).
- Includes a helper function to predict whether new text is human-written or AI-generated.

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/human-vs-ai-classifier.git
cd human-vs-ai-classifier
pip install -r requirements.txt
