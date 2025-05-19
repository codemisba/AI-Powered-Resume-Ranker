
# AI Powered Resume Ranker 

**AI Powered Resume Ranker** is a smart web application that evaluates how closely a resume matches a job description using semantic similarity and keyword extraction. This tool empowers job seekers to tailor their resumes for better alignment with job postings and receive personalized improvement suggestions with the help of AI.

## 🚀 Features

- 📄 Upload your **resume (PDF)** and **job description (TXT)**
- 🧠 Compute **semantic similarity** using SBERT (Sentence-BERT)
- 🔍 Extract top keywords from both documents using **YAKE**
- 📊 View a **match score** and **keyword comparison**
- 💬 Get resume **improvement tips from ChatGPT** based on detected gaps


## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **NLP Models**: SentenceTransformers (SBERT), YAKE
- **AI Assistant**: OpenAI ChatGPT API
- **Utilities**: PyPDF2 for reading PDF files, Python libraries

## 🧩 How It Works

1. **Resume & JD Upload**: Users upload a resume and a job description.
2. **Text Extraction**: Raw text is extracted and cleaned.
3. **Embedding Generation**: SBERT encodes texts into embeddings.
4. **Similarity Scoring**: Cosine similarity measures textual match.
5. **Keyword Extraction**: YAKE identifies and compares keywords.
6. **AI Suggestions**: ChatGPT provides context-aware suggestions.

## 📌 Use Cases

- 🎯 Job seekers tailoring resumes to specific roles
- 🤖 Recruiters evaluating resume-to-job fit
- 🎓 Career advisors helping students or clients improve resumes


## ▶️ Run the App Locally

```bash
git clone https://github.com/your-username/ai-powered-resume-ranker.git
cd ai-powered-resume-ranker
pip install -r requirements.txt
streamlit run app.py
