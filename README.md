🤖 AI Interview Trainer Agent

Personalized, intelligent, and real-time job interview preparation assistant built with **IBM watsonx.ai** and powered by **Retrieval-Augmented Generation (RAG)**.

> “Level up your interview game with AI — confident, role-specific, and always ready.”

---

## 📚 Table of Contents

- [✨ Project Summary](#-project-summary)
- [🎯 Problem Addressed](#-problem-addressed)
- [✅ Solution Overview](#-solution-overview)
- [💡 Key Features](#-key-features)
- [🛠 Technology Stack](#-technology-stack)
- [🏗️ Architecture](#️-architecture)
- [🚀 Live Demo](#-live-demo)
- [🧠 Knowledge Base](#-knowledge-base)
- [🔮 Roadmap](#-roadmap)
- [⚠️ Challenges & Learnings](#️-challenges--learnings)
- [🤝 Acknowledgements](#-acknowledgements)

---

## ✨ Project Summary

The **AI Interview Trainer Agent** is your intelligent interview coach. Built on IBM watsonx.ai and using a RAG architecture, it delivers personalized, real-time interview tips for *any* job role, combining curated internal knowledge and autonomous web search. 

✅ Tailored Prep | ✅ Real-Time Guidance | ✅ Behavioral & Technical Advice

---

## 🎯 Problem Addressed

Most interview prep tools suffer from:

- 🧩 Generic & One-size-fits-all tips
- ⏳ Time-consuming research across multiple sources
- ❌ Lack of personalization to user roles & levels

---

## ✅ Solution Overview

Our AI Agent tackles these issues with:

- 🎯 **Intent Recognition** to detect job role & user needs  
- 🔍 **RAG-Based Info Retrieval** (curated KB + web search)  
- 💬 **Expert Answer Generation** using IBM Granite LLM  

---

## 💡 Key Features

- 🧑‍🎓 **Role-Specific Questions** (e.g., Developer, PM, Data Scientist)  
- 🌍 **Dynamic Web Search** for uncovered roles (e.g., Marine Biologist)  
- 🎯 **Behavioral + Technical Advice**  
- 🪄 **Actionable STAR Method Tips**  
- 🤝 **Empathetic, User-Friendly Interaction**  
- 🚫 **Strict Scope Control** (interview prep only)

---

## 🛠 Technology Stack

| Component           | Technology         |
|---------------------|--------------------|
| 💻 Platform         | IBM Cloud (Lite Tier) |
| 🧠 AI Engine        | IBM watsonx.ai + Granite LLM |
| 🛠 Dev Tools        | IBM Cloud Agent Lab |
| 🗂️ KB Storage      | IBM Cloud Object Storage |
| 🔎 External Search  | Google Search Tool |
| 🧠 RAG Framework    | Custom vector DB + tool routing |

---

## 🏗️ Architecture

```mermaid
graph TD;
    A[User Query] --> B{Role Detected?};
    B -- Yes --> C[Search Internal KB (Vector)];
    B -- No --> D[Trigger Google Search Tool];
    C & D --> E[Generate Response using IBM Granite];
    E --> F[User Output];
```

1. Intent detected from user query  
2. Retrieves info from curated KB or triggers live Google Search  
3. IBM Granite LLM synthesizes and delivers natural response  

---

## 🚀 Live Demo

🔗 **Try It Yourself**:  
👉 [Public Agent URL – Paste Yours Here]

🗨️ Sample Prompts:
- `"Hi, I’m preparing for a Data Scientist interview."`  
- `"Give me behavioral questions for Project Manager."`  
- `"What are your weaknesses?"`

---

## 🧠 Knowledge Base

All role-specific content is stored in:

📁 `interview_trainer_all_roles_kb.txt`  
It includes technical Qs, behavioral scenarios, STAR examples, and role-based strategy.

---

## 🔮 Roadmap

- 🧪 Mock Interview Simulations w/ scoring  
- 📄 Resume/Job JD Analyzer (keyword mapping)  
- 🎙 Voice Interaction (speech-to-text/text-to-speech)  
- 🌐 Multilingual Support  
- 📲 Mobile App  
- 📈 Trend-based Interview Topics  
- 👤 Progress Tracker & Learning Paths  

---

## ⚠️ Challenges & Learnings

- 🎯 Complex Prompt Engineering for role-first logic  
- 🔧 RAG Tool Routing Optimization  
- 🧪 LLM fine-tuning for natural yet focused flow  
- ☁️ Hands-on experience with IBM Cloud + watsonx.ai Studio  

---

## 🤝 Acknowledgements

This project was created under the **IBM SkillsBuild for Academia** initiative.  
Special thanks to the **Edunet Foundation** for mentorship and resources.

---

## 📄 License

This project is for educational purposes only under the IBM SkillsBuild program.
