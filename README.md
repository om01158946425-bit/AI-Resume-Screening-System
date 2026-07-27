🤖 AI Resume Screening System

An AI-powered resume screening system built with n8n, Google Gemini AI, Google Drive, Google Sheets, and Telegram.

The workflow automatically scans all PDF resumes from a Google Drive folder, extracts the text, analyzes each CV using Google Gemini AI, calculates a candidate score based on predefined hiring criteria, stores the results in Google Sheets, ranks all applicants, and sends the Top 5 candidates directly to Telegram.

✨ Features
📂 Automatically scans all PDF resumes in a Google Drive folder
📄 Extracts text from PDF files
🤖 Uses Google Gemini AI to analyze resumes
👤 Extracts:
Full Name
Email
Phone Number
Skills
Years of Experience
Education
Certifications
📊 Calculates an AI hiring score (0–100)
📝 Saves candidate data to Google Sheets
🏆 Ranks candidates by score
📱 Sends the Top 5 candidates to Telegram
⚡ Fully automated using n8n
🛠 Tech Stack
n8n
Google Gemini AI
Google Drive API
Google Sheets API
Telegram Bot API
JavaScript
🔄 Workflow
Search PDF Resumes
        ↓
Loop Through Files
        ↓
Download PDF
        ↓
Extract Text
        ↓
Google Gemini AI
        ↓
Parse JSON
        ↓
Append to Google Sheets
        ↓
Retrieve All Candidates
        ↓
Sort by Score
        ↓
Top 5 Candidates
        ↓
Send Telegram Notification
📊 AI Evaluation Criteria
Criteria	Weight
Skills	40%
Experience	35%
Education	15%
Certifications	10%
🚀 Automation Highlights
Zero manual resume screening
Batch processing of unlimited resumes
AI-powered candidate ranking
Automated HR notification
Easily customizable scoring logic
📸 Demo

Add screenshots of:

n8n Workflow
Google Sheets Results
Telegram Notification
Google Drive Folder
📂 Project Structure
AI-Resume-Screening-System/
│
├── workflow.json
├── README.md
├── screenshots/
├── sample-cvs/
└── docs/
👨‍💻 Author

Omar Mohamed Abdel Hamid

Automation Engineer | AI Automation Developer

GitHub:
https://github.com/om01158946425-bit
LinkedIn:
https://www.linkedin.com/in/omar-mohamed-b17731343/
LinkedIn:
https://www.linkedin.com/in/omar-mohamed-b17731343/
