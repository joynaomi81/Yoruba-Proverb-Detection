# 🌟 OWE-YOR: Leveraging Transformer-Based Models for Yoruba Proverb Classification

**OWE-YOR** is a state-of-the-art NLP project that focuses on the classification of **Yoruba proverbs** using Transformer-based models. It distinguishes between proverbs and non-proverbs, leveraging modern AI to preserve Yoruba language and culture.  

---

## 🚀 Project Workflow

- [Introduction](#introduction)  
- [Features](#features)  
- [Dataset](#dataset)  
- [Models](#models)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Future Work](#future-work)  
- [Team](#team)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  

---

## 📝 Introduction

Yoruba proverbs are rich in cultural and linguistic meaning. Automating their detection is challenging due to limited annotated data. **OWE-YOR** uses Transformer-based models like **AfroLM** and **mBERT** to capture semantic and contextual subtleties, outperforming traditional machine learning models like Naive Bayes.  

**Goals of this project:**  
- Build an automated Yoruba proverb detection system ✅  
- Compare traditional ML and Transformer-based approaches ⚡  
- Contribute to AI tools for African languages 🌍  

---

## ✨ Features

- Detects Yoruba proverbs vs. non-proverbs  
- Uses **Transformer-based models** for high accuracy  
- Provides a **Streamlit demo** for interactive testing  
- Easily extensible to other low-resource African languages  

---

## 📂 Dataset

- **Proverbs:** labeled `1`  
- **Non-proverbs:** labeled `0`  
- Data is **cleaned and preprocessed** for optimal training.  

> Dataset link: [Add your dataset link here]  

---

## 🤖 Models

- **Multinomial Naive Bayes** – baseline performance  
- **AfroLM** and **mBERT** – Transformer-based classification  

**Performance Comparison Example:**  

| Model                   | Accuracy |
|-------------------------|---------|
| Multinomial Naive Bayes | 85%     |
| AfroLM / mBERT          | 92–95%  |

> Transformers better capture semantic context in Yoruba proverbs 🌟  

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/OWE-YOR.git
cd OWE-YOR
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt


🌐 Demo

Try the web app live on Hugging Face Spaces:

🎯 OWE-YOR: Yoruba Proverb Classifier

📊 Results

High accuracy in classifying Yoruba proverbs vs. non-proverbs

Transformers outperform traditional ML in low-resource languages

Confusion matrix and metrics available in results/ folder

🔮 Future Work

Expand to other African languages 🌍

Integrate into culturally-aware conversational AI systems 💬

Explore tone-aware models for tonal languages like Yoruba 🎵

👥 Team

Olusanya Joy – GitHub

Your Partner's Name – GitHub

📜 License

MIT License. See LICENSE
 for details.

🙏 Acknowledgements

Kwame AI and FriendnPal for resources

Hugging Face for pretrained models (AfroLM, mBERT)

Open Speech and Language Resources (OSLR) for dataset support
