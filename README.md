🚀 AI Resume Screening System
📌 Overview

An AI-based system that evaluates resumes against a job description using LangChain + OpenAI.
It generates a score (0–100) and explains the result.

🧠 Pipeline

Resume → Extract → Match → Score → Explain

⚙️ Tech Stack
Python
LangChain
OpenAI API
LangSmith (Tracing)
📂 Structure
prompts/   → Prompt templates  
chains/    → Pipeline logic  
data/      → Resumes + Job Description  
main.py    → Run file  
▶️ Run
pip install -r requirements.txt
python main.py
📊 Output
Fit Score (0–100)
Explanation
🔍 Features

✔ Skill extraction
✔ Matching logic
✔ Explainable AI
✔ LangSmith tracing
