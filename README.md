# chatbot_nlp

# Chatbot Project: Health-Themed Conversational AI

This repository contains the implementation of a health-themed chatbot designed to provide accurate and helpful responses to user queries related to health and wellness. The chatbot combines static responses, semantic matching, and dynamic AI integration to deliver meaningful conversations.

## 📄 Notebook: `chatbot.ipynb`
The notebook demonstrates the design and development of a multi-layered chatbot with the following key features:
- **Static Q&A**: Responds to common health-related questions using a predefined JSON dataset.
- **Vector Similarity Matching**: Finds the closest match for queries that are not directly covered by static responses.
- **Dynamic Intelligence**: Uses Google’s Generative AI API for handling complex and open-ended queries.

---

## 🔑 Features
1. **Static Responses**: 
   - Handles frequently asked questions (FAQs) using a JSON-based dataset.
   - Efficient for predictable and repetitive queries.
   
2. **Semantic Matching**: 
   - Uses pre-trained Word2Vec embeddings (`word2vec-google-news-300`) to calculate query similarity.
   - Ensures smooth handling of queries with slight variations in wording.

3. **Dynamic API Integration**:
   - Incorporates Google’s Generative AI API to respond intelligently to questions outside the scope of static data.

---

## ⚙️ Tools and Technologies
- **Programming Language**: Python
- **Libraries**: 
  - `spaCy` and `NLTK` for preprocessing.
  - `NumPy` for vector calculations.
  - `gensim` for Word2Vec embeddings.
  - `google.generativeai` for dynamic query responses.
- **Platform**: Developed and tested on Google Colab with NVIDIA T4 GPUs.

---

## 🚀 Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/essiaajroud/chatbot_nlp.git
   cd chatbot_nlp
