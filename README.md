# 🧠 AI Resume Analyzer

An AI-powered web application that analyzes resumes to extract key skills and match them with the most suitable job roles using Natural Language Processing (NLP). Built with **Flask**, **HTML/CSS/JS**, and **Python**, this tool helps streamline the candidate evaluation process.

---

## 🔍 Features

- 📄 Upload resumes in PDF or DOCX format  
- 🧠 Extracts important keywords (skills, tools, technologies)  
- 🎯 Matches resumes to 40+ job roles (Data Scientist, AI Engineer, etc.)  
- 📊 Displays skill match percentage using Chart.js  
- ✅ User-friendly interface with secure file handling  

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python)  
- **Frontend**: HTML, CSS, JavaScript  
- **Visualization**: Chart.js  
- **Text Extraction**: Custom Resume Parser  
- **Data**: `roles.json` for job-role keyword mapping  

---

## 📁 Project Structure

```
resume-analyzer/
├── app.py                 # Main Flask app
├── resume_parser.py       # Resume text extraction logic
├── analyzer.py            # Keyword extraction and analysis
├── roles.json             # Job roles and associated keywords
├── uploads/               # Folder for uploaded resumes
│
├── templates/
│   └── index.html         # Frontend UI
│
├── static/
│   ├── style.css          # CSS styling
│   └── script.js          # JavaScript (optional)
│
└── README.md              # Project documentation
```

---

## ⚙️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Flask server:

```bash
python app.py
```

4. Open your browser and go to:  
`http://localhost:5000`

---

## 📄 License

This project is licensed under the **MIT License** © 2025 **Prakash Chauhan**.

---

## 🙋‍♂️ Author

**Prakash Chauhan**  
[GitHub](https://github.com/PrakashSingh785)  
[LinkedIn](https://www.linkedin.com/in/prakash-singh-8a6b18338/)

---

## ⭐ Support

If you like this project, please give it a ⭐ and share it!
