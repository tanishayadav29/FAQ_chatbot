# 🤖 CodeAlpha FAQ Chatbot

A simple AI-inspired FAQ Chatbot built using Python and Streamlit.  
This chatbot answers user questions by matching them with the most relevant FAQ using NLP techniques.

---

## 📌 Project Objective

Build a chatbot that:

- Collects Frequently Asked Questions (FAQs)
- Preprocesses text using NLP
- Matches user queries with similar FAQs
- Returns the best answer
- Provides an interactive chat interface

---

## 🚀 Features

✅ FAQ-based chatbot  
✅ Natural Language Processing (NLP)  
✅ Text preprocessing  
✅ Similarity matching  
✅ Interactive Streamlit UI  
✅ Fast response generation  

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- NLTK

---

## 📂 Project Structure

```plaintext
CodeAlpha_FAQ_chatbot/
│
├── app.py
├── chatbot.py
├── faq_data.csv
├── requirements.txt
├── README.md
```

---

## 📊 Working Process

### 1. Data Collection
Collect FAQ questions and answers in CSV format.

Example:

| Question | Answer |
|---------|--------|
| What is Python? | Python is a programming language |
| What is NLP? | NLP stands for Natural Language Processing |

---

### 2. Text Preprocessing

The chatbot preprocesses user text using:

- Lowercasing
- Tokenization
- Cleaning

---

### 3. Similarity Matching

The system:

- Converts text into vectors
- Calculates cosine similarity
- Selects the closest FAQ
- Displays the answer

---

## ⚙️ Installation

Clone repository:

```bash
git clone https://github.com/your-username/CodeAlpha_FAQ_chatbot.git
```

Move into folder:

```bash
cd CodeAlpha_FAQ_chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run project:

```bash
streamlit run app.py
```

---

## 📸 Output

User enters a question →  
Chatbot processes →  
Most relevant answer is displayed.

---

## 📌 Future Improvements

- Voice support
- Better UI
- AI integration
- Multi-language support

---

## 👩‍💻 Developed By

Tanisha Yadav

For CodeAlpha Internship
