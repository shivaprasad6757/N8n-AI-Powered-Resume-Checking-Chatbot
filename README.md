# 🤖 AI-Powered Resume Checking Chatbot
#### Built with n8n • Google Gemini LLM • Telegram Bot • Resume Parsing Automation
This repository contains a fully automated Resume Screening & Feedback Chatbot built using n8n, designed to help students, job seekers, mentors, and placement teams evaluate resumes instantly and efficiently.

The system reads resumes uploaded via Telegram, extracts all key information, evaluates the content using an LLM, and returns personalized feedback in real time — all without any manual intervention.

**🔍 Project Overview**
- **The chatbot interacts with users through Telegram and automates the entire resume evaluation process. Once a resume is uploaded, the system:**
- ✔ Extracts text (PDF / ZIP → Text)
- ✔ Identifies key sections
- Skills
- Experience
- Education
- Certifications

- **✔ Matches resume content to predefined job roles**
- **✔ Performs gap analysis using Google Gemini LLM**
- **✔ Generates detailed feedback including:**

- Strengths
- Weaknesses
- ATS score
- Formatting corrections
- Missing skills
- Suggestions to improve

**✔ Sends personalized feedback to the user instantly**
**⚙️ Tech Stack & Workflow**
**🔧 Technologies Used**
- n8n Workflow Automation
- Telegram Bot API
- PDF-to-Text Resume Parser
- Google Gemini LLM for evaluation
- Switch / IF Nodes for scoring and logic flow
- Chat-based response delivery

**🧠 Workflow Summary**

**1)Telegram Trigger Node**
- Captures resume files from users.

**2)File Handling + Parsing**
- Extracts text from uploaded PDFs or ZIP files.

**3)Resume Analysis Node (LLM)**
- Evaluates skills, education, experience, tone, formatting, and structure.

**4)ATS Scoring Logic**
- Uses conditional nodes to assign an estimated ATS score.

**5)Gap Analysis + Suggestions**
- LLM generates targeted recommendations.

**6)Telegram Reply Node**
- Sends detailed feedback back to the user.

**🎯 Key Features**
- 🔹 100% automated resume evaluation
- 🔹 Smart skill-gap analysis using LLM
- 🔹 ATS-style scoring for accuracy
- 🔹 Personalized improvement suggestions
- 🔹 Fast & scalable for institutions
- 🔹 Consistent and reliable assessments
- 🔹 Perfect for student training & placement departments

**📈 Impact**

- **This automation:**

- ✔ Greatly reduces manual evaluation work
- ✔ Helps students improve resumes instantly
- ✔ Provides HR-style standardized feedback
- ✔ Improves job readiness and confidence
- ✔ Scales seamlessly across large student batches

**By combining AI + automation, the system delivers practical real-world value, speed, and accuracy.**

**🚀 How to Use**
- Clone this repository
- Import the .json workflow into your n8n instance
- Set up your Telegram bot token
- Add your Google Gemini API key
- Configure the resume parser node
- Activate the workflow

**Upload a resume via Telegram and get instant feedback 🎉**

**🧠 Skills Strengthened**
- AI automation using n8n
- Resume parsing & document processing
- LLM prompt engineering
- ATS scoring logic
- Telegram chatbot design
- End-to-end workflow development
- Real-world automation architecture

