#  CHATBOT WITH SENTIMENT ANALYSIS
Human-like sentiment analysis chatbot deployed on Hugging Face using Gradio, with implementing Tier-1 and Tier-2 sentiment analysis.

A **production-ready Sentiment Analysis Chatbot** built using **Pure Python** with an advanced **rule-based NLP engine**, **smart contextual responses**, and a **modern Gradio web interface**.  
The chatbot analyzes user messages in real-time and classifies sentiment as **Positive, Neutral, or Negative**, along with detailed conversation-level analytics. 


🌍 Deployment:- 

 Quick Start
🌐 Live Demo on Hugging Face Spaces

Try it now without any installation!

<img width="889" height="863" alt="image" src="https://github.com/user-attachments/assets/001532ab-b995-4df7-a403-490e2b6aae80" />

🔗 Live App: [ https://huggingface.co/spaces/ShaliniDS13/ChatBot]

No setup required - just click and start chatting with sentiment analysis!

---

## ✨ Key Features

- ✅ Statement-level sentiment analysis (Tier-2)
- ✅ Conversation-level sentiment analysis (Tier-1)
- ✅ Sentiment trend detection (Improving / Declining / Stable)
- ✅ Confidence score for each sentiment
- ✅ Smart, context-aware chatbot responses
- ✅ Rule-based NLP (no ML model required)
- ✅ Export conversation history as JSON
- ✅ Interactive terminal chatbot
- ✅ Clean and modern Gradio web UI
- ✅ Production-ready, well-structured code

---

## 🧠 Sentiment Categories

| Sentiment | Emoji |
|---------|-------|
| Positive | 😊 |
| Neutral  | 😐 |
| Negative | 😞 |

---
🧪 Example Interaction 

User Input:

I am very happy with your support!

Output:

Sentiment: 😊 Positive
Confidence: High
Bot: I'm glad to hear that! How can I assist you further?

📊 Conversation Analysis Output:-
{
  "overall_sentiment": "Positive",
  "average_score": 0.62,
  "trend": "Improving",
  "sentiment_distribution": {
    "Positive": 60,
    "Neutral": 20,
    "Negative": 20
  }
}



## 🛠️ Tech Stack

- Python  
- Gradio (Interactive Web UI)  
- NLTK (Natural Language Toolkit for text processing)  
- Colorama (Colored terminal output)  
- Dataclasses (Structured data models)  
- Rule-Based Natural Language Processing (NLP)  
- Text Preprocessing (Tokenization, Lowercasing)  
- Context-Aware Response Generation  
- Sentiment Scoring & Confidence Calculation  
- Conversation-Level Analytics  
- Sentiment Trend Analysis  
- Hugging Face Spaces (Deployment)  
- GitHub (Version Control & Collaboration)  


---  

## 🧩 Core Components

### 📁 liaplus_chatbot.py

#### 🔹 Data Models
- **SentimentResult**  
  Represents sentiment analysis output  
  (label, score, confidence)

- **Message**  
  Stores conversation messages with timestamp and sentiment details  

---

#### 🔹 Sentiment Engine
- **RuleBasedSentimentAnalyzer**
  - 50+ positive sentiment keywords  
  - 45+ negative sentiment keywords  
  - Intensifier detection (very, extremely, highly, etc.)  
  - Negation handling (not, never, don't, etc.)  
  - Confidence score calculation  

---

#### 🔹 Response Generator
- **SmartResponseGenerator**
  - Keyword detection (price, support, feature, problem)  
  - Context-aware response templates  
  - Dynamic responses based on sentiment and conversation flow  

---

#### 🔹 Analytics
- **ConversationAnalyzer**
  - Overall conversation sentiment analysis  
  - Sentiment distribution (Positive / Neutral / Negative)  
  - Sentiment trend analysis (Improving / Declining / Stable)  


