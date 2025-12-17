# ✈️ Airline Customer Strategy & Intelligence Agent

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-ff4b4b)
![OpenAI](https://img.shields.io/badge/AI-GPT--3.5-green)
![Status](https://img.shields.io/badge/Status-Prototype-orange)

### **Transforming Unstructured Feedback into Roadmap Priorities**

This repository hosts a **Strategic Analyst Agent** designed for the airline industry. It solves a core problem in Customer Experience (CX): transforming thousands of unstructured reviews into an actionable business strategy.

Instead of static reports, this dashboard utilises **Generative AI (LLMs)** to automate segmentation, detect churn risks, and answer complex stakeholder questions in real-time.

---

## 🚀 Key Features

### **1. 📊 Automated Segmentation**
* **The Problem:** Airlines often treat all economy passengers the same.
* **The Solution:** The tool analyses context clues in reviews to instantly categorize travelers into **Business** vs. **Leisure** segments, enabling targeted loyalty strategies for SMBs.

### **2. ⚔️ Competitive Radar (Churn Detection)**
* **The Problem:** Knowing *that* a customer is unhappy is easy; knowing *who* they are switching to is hard.
* **The Solution:** The system flags reviews where high-value flyers explicitly mention competitors (e.g., *"Switching to Delta due to lounge access"*), identifying the specific root cause of the threat.

### **3. 🤖 The Strategic Analyst Agent (AI)**
* **The Problem:** Stakeholders have ad-hoc questions that static dashboards can't answer.
* **The Solution:** An integrated **LangChain + OpenAI** agent allows executives to ask questions in plain English, such as:
    * *"What are the top complaints from business travellers this week?"*
    * *"Draft an apology email to customers affected by baggage delays."*

---

## 🛠️ Tech Stack

* **Language:** Python 3.10
* **Frontend:** Streamlit
* **AI/LLM:** OpenAI API (GPT-3.5 Turbo), LangChain
* **Data Processing:** Pandas, NumPy, TextBlob (Sentiment Analysis)
* **Visualization:** Plotly Express

---

## 🎥 Demo

> **[Click here to watch the 60-second Video Demo on LinkedIn](https://www.linkedin.com/posts/darshan0411_python-streamlit-llms-activity-7406853539626442752-aGAG?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAmSaSIBbI8gneECH-SDLq7zMyUzeF4MNcY)**

---

## 💻 Installation & Usage

To run this dashboard locally, follow these steps:

**1. Clone the repository**
```bash
git clone [https://github.com/yourusername/airline-strategy-agent.git](https://github.com/yourusername/airline-strategy-agent.git)
cd airline-strategy-agent
