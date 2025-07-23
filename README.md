# AI-Resume-Critiquer
A simple and interactive web app built with Streamlit that allows users to upload their resumes (PDF or TXT) and receive AI-powered constructive feedback to improve clarity, skills presentation, and experience descriptions. The app can also tailor recommendations based on the specific job role targeted.


# AI Resume Critiquer

An interactive web app built with **Streamlit** and powered by **OpenAI GPT** that analyzes your resume and provides personalized, AI-generated feedback.

🎯 Upload your resume (PDF or TXT)  
🧠 Get smart suggestions for improvement  
💼 Tailor it for a specific job role  
📄 Improve clarity, skills, and experience presentation

---

## 🚀 Features

- ✅ Upload your resume as a `.pdf` or `.txt` file
- 🎯 Enter a job role to customize feedback
- 🤖 AI analyzes content clarity, skill relevance, and experience descriptions
- 📈 Provides structured, actionable recommendations

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [OpenAI GPT API](https://platform.openai.com/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [dotenv](https://pypi.org/project/python-dotenv/)

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/bulachidaniela/AI-resume-critiquer.git
cd AI-resume-critiquer

2.Create and activate a virtual environment:
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
.venv\Scripts\activate     # Windows

3.Install the required packages:
pip install -r requirements.txt

4.Create a .env file and add your OpenAI API key:
OPENAI_API_KEY=your_openai_api_key_here

RUN THE APP
streamlit run app.py
