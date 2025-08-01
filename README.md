# 🤖 Research Agent – AI-powered Academic Assistant (IBM Cloud)

An AI-powered Research Agent built entirely on **IBM Cloud** using **Watsonx.ai**, **Granite foundation models**, and **Agent Lab**, designed to revolutionize academic and scientific research workflows.

---

## 📌 Problem Statement No. 1 – Research Agent

The Challenge- A Research Agent is an AI system designed to assist with academic and scientific
research tasks. It can autonomously search for literature, summarize papers, and organize references.
Using natural language processing, it understands research questions and retrieves relevant
information.
The agent can generate reports, suggest hypotheses, and even draft sections of research papers.
It saves time by automating repetitive tasks like citation management and data extraction.
Research Agents enhance efficiency, accuracy, and innovation in both academic and industrial R&D.


This project fulfills these capabilities using IBM’s Cloud Lite services and Watsonx tools.

---

## 🧠 Technologies Used

| Technology         | Purpose                                |
|--------------------|----------------------------------------|
| IBM Watsonx.ai     | Model building & deployment            |
| Granite Model (`granite-3-3-8b-instruct`) | Foundation LLM  |
| Agent Lab          | No-code agent builder (LangGraph + ReAct)|
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

ResearchAgent/
├── Code Snippets/
│ ├── Python.py
│ └── java.txt
├── Deployment/
│ ├── Add deployment space.png
│ └── deployed status.png
├── Outputs/
│ ├── output (1).png ... output (6).png
├── Project Creation/
│ ├── Cloud Storage.png
│ ├── Dashboard.png
│ ├── Vectorized document.png
│ ├── Watsonx.ai Project.png
│ ├── agent lab.png
│ ├── granite model.png
│ ├── project name.png
│ ├── watsonx dashboard.png
│ ├── watsonx.ai runtime.png
├── exported agent/
│ ├── assets/
│ │ └── vector_index/
│ ├── assettypes/
│ └── project.json
├── README.md
├── api references.png
├── deployed Agent.png
└── research-paper-sample.docx
---

## 🚀 Features

- 📄 Upload PDFs, DOCX, TXT files for indexing
- 🔎 Ask contextual questions from documents
- ✨ Summarize or extract key points from research
- 🧠 Uses advanced LLMs for inference
- 🧰 Custom tools like Google Search integrated

---

## 📦 How to Use

> Note: This project is built fully inside IBM Watsonx and **does not require cloning or running code manually**.

1. Go to your Watsonx project dashboard.
2. Import documents into **Vector Index** (e.g., `research.pdf`).
3. Ask questions like:
   - *“Summarize the document”*
   - *“What are the main findings?”*
   - *“List the cited works”*
4. Preview outputs in Agent Lab or deploy it as a service.

---

## 📁 Deployment

- Navigate to the **Deployment tab** on Watsonx.
- Ensure API Key is configured.
- Click **Deploy as AI Service**.
- Use the **Preview** tab to test responses.
- Optionally connect to external apps using the **API reference**.

---

## 📌 Screenshots

Screenshots of key steps are included in:

- `Project Creation/` – Watsonx environment setup
- `Deployment/` – Service deployment details
- `Outputs/` – Response examples
- `exported agent/` – JSON export and asset vector index

---

## ✅ Status

**Completed** and successfully deployed. Ready to demonstrate research document understanding and interaction.

---

## 📜 License

This project is part of the **IBM SkillsBuild Sandbox Program** and intended for educational/demo purposes.

---

## 🙋‍♂️ Author

**Aditya Ohdar**  
Research Agent Builder | IBM Cloud | AI Enthusiast  
📧 [adityaohdar24@gmail.com](mailto:adityaohdar24@gmail.com)

