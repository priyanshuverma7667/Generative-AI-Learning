# Generative AI Learning: Text Preprocessing & Tokenization

Welcome to the **Generative-AI-Learning** repository! This project serves as a foundational learning guide for Natural Language Processing (NLP) and Generative AI text preprocessing workflows. Before text data can be fed into Large Language Models (LLMs) or neural networks, it must be cleaned, structured, and broken down into tokens.

This repository covers essential text-cleaning methodologies and tokenization practices using Python and the Natural Language Toolkit (NLTK).

## 📂 Repository Structure

The repository automatically documents its contents. Current interactive notebooks:

*   **Text_Cleaning_Punctuation&White_Space.ipynb**
*   **Tokenization_using_NLTK.ipynb**

## 🚀 Getting Started

### 1. Clone the Repository
Begin by cloning this repository to your local machine using git:
```bash
git clone https://github.com
cd Generative-AI-Learning
```

### 2. Set Up a Virtual Environment (Recommended)
Keep your dependencies isolated by setting up a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Dependencies
Install Jupyter Notebook along with NLTK to interact with the code:
```bash
pip install jupyter nltk
```

### 4. Download NLTK Models
The tokenization notebooks require NLTK's pre-trained tokenization models. Run Python in your terminal and download the `punkt` dataset:
```python
import nltk
nltk.download('punkt')
```

---

## 📝 License
This project is open-source and available for educational and learning purposes.
