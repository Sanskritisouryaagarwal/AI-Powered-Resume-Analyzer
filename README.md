# 📄 AI-Powered Resume Analyzer

An intelligent, HR-style assistant built with Google Generative AI to analyze resumes, assess job compatibility, and suggest actionable career improvements. This tool simplifies the resume review process using AI-driven insights, making it useful for both job seekers and recruiters.

![Untitled design (3)](https://github.com/user-attachments/assets/69b5967b-b80e-4e4f-b7e5-dfee80dff99a)

---

## 📋 Project Overview
The **AI-Powered Resume Analyzer** is a virtual HR assistant that mimics the behavior of a seasoned recruiter. It analyzes uploaded resumes and delivers structured feedback on how well the resume aligns with job descriptions. This application is designed to:

- Help job seekers polish and optimize their resumes.
- Assist recruiters in shortlisting resumes based on skill-job compatibility.
- Provide career guidance through personalized feedback and upskilling suggestions.

Whether you are preparing for your first job or switching roles, this tool empowers you with data-backed insights to elevate your resume quality and job readiness.

---

## 🔑 Key Features

### 🧾 General Resume Analysis
- 📌 **One-Line Summary:** Condenses the essence of the resume.
- 🧠 **Skill Identification:** Highlights key technical and soft skills found.
- 🧩 **Skill Gap Analysis:** Points out what’s missing for a competitive edge.
- 📚 **Course Recommendations:** Suggests relevant online courses based on industry trends.
- 📈 **Strengths & Weaknesses:** Breaks down strengths in experience and areas that need improvement.

### 📝 Resume Matching with Job Description
- 📊 **Match Score:** Provides a percentage-based compatibility score with the target job.
- ❌ **Missing Skills:** Lists skills present in the job description but absent in the resume.
- ✅ **Job Readiness Verdict:** Recommends whether the resume is ready for application or needs adjustments.
![Untitled design (4)](https://github.com/user-attachments/assets/e6ea01b4-ad3e-40b1-b8af-3cc228444cf0)

---

## 🛠 Tech Stack
| Component           | Technology                        |
|--------------------|------------------------------------|
| **Frontend**       | Streamlit                          |
| **Backend**        | Python                             |
| **AI Engine**      | Google Generative AI (Gemini)      |
| **Resume Parsing** | pdfplumber                         |
| **OCR Fallback**   | pytesseract                        |
| **Env Handling**   | dotenv (`.env` for API key config) |

---

## ⚙️ How It Works

### 📂 Resume Parsing
- Utilizes **pdfplumber** to extract structured text from uploaded PDFs.
- If parsing fails, **pytesseract** performs Optical Character Recognition (OCR) to extract content.

### 🤖 AI-Driven Analysis
- The extracted resume text is sent to **Google Generative AI (Gemini)**.
- Gemini summarizes the content, highlights skills, and identifies improvement areas.
- When provided, it compares resume content with the job description to measure compatibility.

### 💡 Actionable Feedback
- AI returns insights about:
  - Skills to highlight or acquire
  - Course suggestions (e.g., from Coursera, Udemy)
  - Resume’s alignment with the job’s required qualifications

---

## 🔄 Use Cases
- **Job Seekers:** Improve and tailor resumes for specific roles.
- **Career Coaches:** Offer data-backed resume critiques to clients.
- **Recruiters:** Automate initial resume screening based on job fit.

---

## 🙌 Contributing
We welcome collaboration and enhancements! Follow these steps:

1. **Fork** the repository to your GitHub.
2. **Clone** the project locally.
3. **Create** a new feature branch:
```bash
git checkout -b feature/new-enhancement
```
4. **Commit** your changes with clear messages:
```bash
git commit -m "Add skill visualization module"
```
5. **Push** to your forked repository:
```bash
git push origin feature/new-enhancement
```
6. **Submit a Pull Request** and describe your changes.

---

## 📜 License
This project is open-source under the **MIT License** — feel free to modify, reuse, or contribute.

---

## 👩‍💻 Author
Developed by **Sanskriti Sourya**  
🔗 [LinkedIn](https://www.linkedin.com/in/sanskriti-sourya)  
🐙 [GitHub](https://github.com/sanskriti-sourya)

---

Empower your resume with the insights of AI. ✨

**🔍 Practice Smart. Apply with Confidence.**
