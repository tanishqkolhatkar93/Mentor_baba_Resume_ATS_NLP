# 📄 Smart Resume Analyzer (Domain-Based ATS)

This is a Streamlit-based **Smart Resume Analyzer** tool built for academic or portfolio use. It allows users to:

✅ Select their career domain  
✅ Upload their resume (PDF or TXT)  
✅ Automatically match their skills with the **required skills** for that domain  
✅ See an **ATS (Applicant Tracking System) score**  
✅ Download a CSV report with matched and missing skills

---

## 🚀 Features

- Manual **domain selection** (Data Science, Web Dev, ML, etc.)
- Extracts text from PDF or TXT resume
- Matches your skills against a **predefined skill set**
- Displays:
  - ✅ Matched skills
  - ⚠️ Missing skills
  - 📊 ATS Score
- Downloadable CSV report

---

## 🧠 How Skill Matching Works

- A set of **important skills** for each domain is defined manually
- Your resume is scanned and matched against those using fuzzy logic
- Based on matches, an ATS score is calculated
- Suggestions for improvement are shown

---

## 📁 How to Run

1. **Clone or download** this repository
2. Create a virtual environment (optional but recommended)

   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # For Windows
👨‍💻 Author

Made with ❤️ for academic/project use.


---
## Install dependencies
```bash
pip install -r requirements.txt

```
## Run the app
```bash
streamlit run app.py
```
```bash
Open browser at http://localhost:8501
```
📝 File Structure
Now just make sure your folder includes:

```bash
📁 PROJECT RESUME DETECTION
├── app.py
├── utils.py
├── requirements.txt
└── README.md





# 🧠 Live Resume Skill Analyzer

A smart ATS (Applicant Tracking System) checker built with Streamlit, which analyzes resumes against trending domain-specific skills and generates an ATS Score with improvement suggestions.

## 🚀 Features

📄 Resume Upload – Supports PDF & TXT resumes.

🔍 Live Skill Fetching – Scrapes latest skills for domains like Data Science, Machine Learning, Web Development, etc.

🤖 Fuzzy Matching – Matches resume content with job skills using intelligent text similarity.

📊 ATS Score Calculation – Provides a score (%) based on matched vs missing skills.

💡 Improvement Suggestions – Lists missing skills to help improve resumes.

📥 Downloadable Reports – Export detailed CSV report or Matched Skills list.

🎨 Clean UI/UX – Interactive dashboard built with Streamlit.

🛠️ Tech Stack

Frontend & UI: Streamlit

Backend Logic: Python (Pandas, RapidFuzz)

Text Extraction: PyPDF2 (for PDF resumes)

Data Handling: Pandas, CSV reports

Skill Fetching: Web scraping module (custom)

📂 Project Structure
📦 resume-skill-analyzer
 ┣ 📜 app.py                 # Main Streamlit app
 ┣ 📜 utils.py               # Helper functions (e.g., PDF text extraction)
 ┣ 📜 web_scraper.py         # Fetch latest skills per domain
 ┣ 📜 requirements.txt       # Dependencies
 ┣ 📜 README.md              # Documentation
 ┗ 📂 sample_data
     ┗ 📄 sample_resume.pdf   # Example resume

⚡ Installation & Usage
1️⃣ Clone Repository
git clone https://github.com/<your-username>/resume-skill-analyzer.git
cd resume-skill-analyzer

2️⃣ Create Virtual Environment & Install Dependencies
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
pip install -r requirements.txt

3️⃣ Run Streamlit App
streamlit run app.py


Your app will be live at 👉 http://localhost:8501

📊 Example Output
Dashboard Preview

Matched Skills: Python, Machine Learning, AWS

Missing Skills: TensorFlow, Docker

ATS Score: 65%

✅ Future Improvements

Add NLP-powered embeddings (e.g., BERT) for deeper semantic matching.

Support multiple resumes & bulk analysis.

Deploy app on AWS/GCP/Streamlit Cloud.

Add role-based ATS benchmarking for specific companies.

🤝 Contributing

Contributions are welcome! Feel free to fork this repo, open issues, and submit PRs.

📜 License

This project is licensed under the MIT License.
