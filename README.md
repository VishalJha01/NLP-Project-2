# 🛒 Customer Support Chatbot for Online Shopping
**By Vishal (Roll No: 2301201222)**  
**Course:** BCA – Section C  

---

## 📚 Overview
This project is a **Customer Support Chatbot** designed to handle common online shopping queries such as order tracking, return policies, delivery times, and product FAQs.  
It combines **Natural Language Processing (NLP)** and **rule-based logic** to understand user queries and deliver instant, accurate responses.

---

## 🎯 Goal
To automate basic customer support tasks for an e-commerce platform by building a chatbot that can recognize intent, extract key information (like order numbers), and respond appropriately.

---

## 🔑 Concepts Used
- **Intent Recognition** – Classifying query type (e.g., order status, return policy)  
- **Named Entity Recognition (NER)** – Extracting entities like order numbers or product names  
- **Text Preprocessing** – Tokenization, stopword removal, and lemmatization  
- **TF–IDF & Cosine Similarity** – For text-based matching  
- **Rule-Based Logic** – For structured, consistent replies  

---

## 🛠 Tools & Libraries
- **Python**  
- **NLTK** – For tokenization, stopword removal, lemmatization  
- **Scikit-learn** – For TF-IDF and cosine similarity  
- **Pandas** – For managing datasets  
- **Regular Expressions (re)** – For order number extraction  

---

## 🧩 Workflow
1. Preprocess the user query (tokenize, remove stopwords, lemmatize).  
2. Classify the **intent** (e.g., Order Status, Return Policy, Product Info).  
3. Extract **entities** (like order numbers) using regex.  
4. Retrieve and return the most suitable response.

---

## 📊 Example Dataset

| Intent | Example Query | Response |
|--------|----------------|-----------|
| Order Status | Where is my order #12345? | Your order #12345 is out for delivery. |
| Return Policy | How can I return a product? | You can return products within 15 days via our online portal. |
| Product Info | Does this phone support fast charging? | Yes, this phone supports fast charging. |

---

## 💻 How It Works (Google Colab or Local)
1. Install dependencies  
   ```bash
   pip install nltk scikit-learn pandas
