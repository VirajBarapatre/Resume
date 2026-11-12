# Viraj Barapatre

**AI and Data Engineer** (entry level) · Nagpur, India

I like building AI that has to be right, not just impressive. My best example is a live RAG chatbot that answers questions about my own work, and only from the documents it's given. I've also built an anomaly detector, a demand forecaster, and CNN image classifiers, co-authored a paper published in IEEE Xplore, and spent six months at a fintech checking 50,000+ transaction records a day.

Resume: [Viraj Barapatre Resume.pdf](Viraj%20Barapatre%20Resume.pdf)

---

## Projects

### Ask My Portfolio: a chatbot that answers questions about me
A RAG chatbot built so a recruiter can just ask it. It splits my documents into chunks, finds the right ones with FAISS, and answers only from them, which keeps it from making things up. Runs on Ollama locally or Groq in the cloud.
**Live demo:** https://virajs-ask-my-portfolio.streamlit.app
Stack: Python, LangChain, FAISS, Groq API, Ollama, Streamlit

### Agentic RAG Portfolio: a tool-calling agent with an evaluation harness
A LangGraph agent that chooses between document search, a calculator, and a read-only SQL tool, or refuses when a question is out of scope. It comes with a 40-question evaluation set scored on tool choice, correctness, and groundedness (35/40 on the first run), a written failure analysis, and a list of reasons the score may be overstated.
Repo: https://github.com/VirajBarapatre/Agentic-RAG-Portfolio
Stack: Python, LangGraph, Groq API, sentence-transformers, FAISS, SQLite, pytest

### AML-Sentinel-AI: spotting unusual transactions
There are no labelled fraud examples to learn from, so the model looks for what doesn't fit (Isolation Forest). I backtested the alert thresholds to cut false positives and mapped risk on geospatial heatmaps.
Stack: Python, scikit-learn, Pandas

### Dynamic Pricing Simulator
A pricing app that forecasts demand, revenue, and profit across 20+ product categories (Random Forest, validation RMSE 13.36). Flask backend, Chart.js charts, deployed on Render.
Stack: Python, Flask, scikit-learn, Chart.js

### CampusEYE: attendance from video
A four-person team project. I built the frontend and tested the models. It became a co-authored paper published in IEEE Xplore (2026 IEEE RECCAP): https://ieeexplore.ieee.org/document/11724117
Stack: React, SmolVLM, YOLOv8

### Medical image classifiers
- [Skin Cancer Detection System](https://github.com/VirajBarapatre/Skin-Cancer-Detection-System): a CNN that classifies skin lesion images into 7 categories, with a Tkinter interface.
- Brain tumor classification from MRI scans (CNN).
- [Text CAPTCHA Solver](https://github.com/VirajBarapatre/Text-CAPTCHA-Solver): a CNN and OCR approach to image-based CAPTCHAs.

---

## Experience

**Data Science & Quantitative Intern**, Trust Fintech Limited, Nagpur (Dec 2025 to June 2026)
- Wrote the Python pipelines that checked 50,000+ multi-source transaction records every day. Processing time dropped by 35% and data integrity held at 99.9%.
- Profiled the data with SQL (PostgreSQL, MySQL), tuned slow queries, and ran performance tests on high-volume logs.
- When numbers didn't match, I traced them back to the source and documented the cause.
- Built Power BI dashboards and automated validation routines for stakeholders.

---

## Skills

- **GenAI and LLM apps:** RAG, LangChain, LangGraph, FAISS, embeddings, prompt engineering, hallucination control, Groq API, Ollama
- **Python and data:** Python, SQL (PostgreSQL, MySQL, SQL Server), Pandas, NumPy, Jupyter, PySpark, Hadoop, MongoDB, ETL pipelines, data validation
- **Machine learning:** scikit-learn, XGBoost, Random Forest, Isolation Forest, feature engineering, CNN and YOLOv8 (project level), PyTorch and TensorFlow (project level)
- **BI and platforms:** Excel (lookups, pivot tables, formulas), Power BI, Tableau (hands-on practice), Airflow, BigQuery, Databricks (fundamentals), Azure Fundamentals (AZ-900 training completed)
- **Building and shipping:** Flask REST APIs, JSON, React, JavaScript, HTML5, Git/GitHub, Docker (basic), CI/CD (basic)
- **Other languages:** C++, R, SAS

---

## Education and certifications

- **B.Tech, Computer Science & Engineering (Artificial Intelligence)**, G.H. Raisoni College of Engineering, Nagpur (June 2026, CGPA 8.09/10)
- SIG CodeSignal 600/600 (100th percentile)
- Oracle OCI 2025 AI Foundations Associate · Codecademy Professional CS Certificate · IIT Bombay PostgreSQL course · Citi and Deloitte Forage simulations

---

## Contact

- Email: virajbarapatre@outlook.com
- LinkedIn: [Viraj Barapatre](https://www.linkedin.com/in/viraj-barapatre)
- Portfolio: https://viraj-portfolio-three.vercel.app
- GitHub: [VirajBarapatre](https://github.com/VirajBarapatre)
