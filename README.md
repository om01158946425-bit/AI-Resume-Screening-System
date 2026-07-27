# 🤖 AI Resume Screening System

An AI-powered resume screening workflow built with **n8n**, **Google Gemini AI**, **Google Drive**, **Google Sheets**, and **Telegram Bot API**.

The system automatically scans PDF resumes from a Google Drive folder, extracts the content, analyzes each CV using Google Gemini AI, calculates a candidate score based on predefined hiring criteria, stores the structured results in Google Sheets, ranks applicants automatically, and instantly notifies the recruiter via Telegram.

---

# 🚀 Features

- 📂 Automatically scans all PDF resumes from a Google Drive folder
- 📄 Downloads every PDF resume
- 📑 Extracts text from PDF files
- 🤖 Uses Google Gemini AI to analyze resumes
- 👤 Extracts candidate information:
  - Full Name
  - Email
  - Phone Number
  - Skills
  - Years of Experience
  - Education
  - Certifications
- 📊 Calculates an AI hiring score (0–100)
- 📁 Stores structured candidate data in Google Sheets
- 🏆 Automatically ranks candidates by score
- 📩 Sends the highest-scoring candidate to Telegram
- ⚡ Fully automated using n8n

---

# 🔄 Workflow

```text
Google Drive Folder
        │
        ▼
Search PDF Resumes
        │
        ▼
Loop Through Files
        │
        ▼
Download PDF
        │
        ▼
Extract Text
        │
        ▼
Google Gemini AI
        │
        ▼
Parse JSON
        │
        ▼
Append to Google Sheets
        │
        ▼
Retrieve All Candidates
        │
        ▼
Sort by Score
        │
        ▼
Select Top Candidate
        │
        ▼
Telegram Notification
```

---

# 📊 AI Evaluation Criteria

| Criteria | Weight |
|-----------|--------|
| Skills | 40% |
| Experience | 35% |
| Education | 15% |
| Certifications | 10% |

---

# 🛠 Tech Stack

- n8n
- Google Gemini AI
- Google Drive API
- Google Sheets API
- Telegram Bot API
- JavaScript

---

# 📂 Project Structure

```text
AI-Resume-Screening-System/
│
├── workflow.json
├── README.md
├── screenshots/
│   ├── workflow.png
│   ├── google-sheets.png
│   └── telegram.png
│
├── sample-cvs/
│
└── docs/
```

---

# ⚙️ How It Works

1. Search all PDF resumes inside a Google Drive folder.
2. Loop through every resume.
3. Download each PDF.
4. Extract the resume text.
5. Send the extracted text to Google Gemini AI.
6. Generate structured JSON containing candidate information.
7. Calculate the candidate score.
8. Save the data into Google Sheets.
9. Retrieve all candidates.
10. Sort candidates by score.
11. Select the highest-scoring candidate.
12. Send the final result to Telegram.

---

# 📄 Example AI Output

```json
{
  "full_name": "John Doe",
  "email": "john@example.com",
  "phone": "+20xxxxxxxxxx",
  "skills": [
    "Python",
    "n8n",
    "Docker",
    "JavaScript"
  ],
  "years_of_experience": 3,
  "education": "Bachelor of Computer Engineering",
  "certifications": [
    "Google AI Essentials",
    "Automation Fundamentals"
  ],
  "score": 89
}
```

---

# 🚀 Automation Highlights

- ✅ Zero manual resume screening
- 📂 Batch processing for unlimited resumes
- 🤖 AI-powered candidate evaluation
- 📈 Automatic candidate ranking
- 📊 Structured Google Sheets database
- 📩 Instant Telegram notification
- ⚡ Fully automated recruitment workflow
- 🔧 Easily customizable scoring logic

---

# 💡 Future Improvements

- Support DOCX resumes
- Email notifications
- HR dashboard
- Duplicate CV detection
- Multi-language resume analysis
- ATS integration
- AI interview question generation
- Candidate shortlisting by department

---

# 👨‍💻 Author

**Omar Mohamed Abdel Hamid**

**Automation Engineer | AI Automation Developer**

### 🌐 Connect with Me

- GitHub: https://github.com/om01158946425-bit
- LinkedIn: https://www.linkedin.com/in/omar-mohamed-b17731343/

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and supports future improvements.

---

# 📜 License

This project is released for educational and portfolio purposes.
