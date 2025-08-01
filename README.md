# 🤖 Research Agent – AI-powered Academic Assistant (IBM Cloud)

An AI-powered Research Agent built entirely on **IBM Cloud** using **Watsonx.ai**, **Granite foundation models**, and **Agent Lab**, designed to revolutionize academic and scientific research workflows.

---

## 📌 Problem Statement No. 1 – Research Agent

A Research Agent is an AI system designed to:
- Autonomously search literature
- Summarize academic papers
- Organize references
- Understand user research queries using NLP
- Generate research reports, suggest hypotheses, and extract insights

This project fulfills these capabilities using IBM’s Cloud Lite services and Watsonx tools.

---

## 🧠 Technologies Used

| Technology         | Purpose                                |
|--------------------|----------------------------------------|
| IBM Watsonx.ai     | Model building & deployment             |
| Granite Model (`granite-3-3-8b-instruct`) | Foundation LLM             |
| Agent Lab          | No-code agent builder (LangGraph + ReAct) |
| IBM Object Storage | PDF upload & vector grounding           |
| IBM Vector Index   | Grounding Gen AI with vectorized docs   |

---

## ⚙️ Features

- 🔍 Summarizes uploaded research papers (PDF, DOCX, TXT)
- 📚 Answers academic questions based on vectorized documents
- 📝 Extracts insights and generates report sections
- 🧠 Understands natural language research queries
- 📖 Supports document grounding via vector index
- 🔌 Optional integration with Google Search (tool)

---

## 📁 Project Structure


---

## 🛠️ How It Was Built

1. **Created a Project** in IBM Watsonx.ai Studio
2. **Added assets** (Notebook + PDF file) or uploaded vector docs
3. **Built agent** using:
   - Framework: `LangGraph`
   - Architecture: `ReAct`
   - Model: `Granite 3-3-8b Instruct`
4. **Grounded agent** with vector index (PDF)
5. **Set instructions** and tuned model parameters
6. **Deployed as an AI Service**
7. ✅ Final Agent Preview – live & working

---

## 🧪 Sample Test Prompts

- “Summarize the key findings of the uploaded research paper.”
- “What are the limitations mentioned in the document?”
- “Generate an introduction section based on this paper.”
- “Suggest possible future work based on this study.”
- “List all the methodologies used.”

---

## 🧠 Agent Instructions Used

```text
You are a helpful assistant that uses tools to answer questions in detail.
When greeted, say "Hi, I am watsonx.ai agent. How can I help you?"

🚀 Deployment Status
✅ Deployed on IBM Watsonx.ai
📡 Status: Online
🔒 Access: Restricted to IBM Cloud account

👨‍💻 Author
Aditya Ohdar
Email: adityaohdar24@gmail.com
