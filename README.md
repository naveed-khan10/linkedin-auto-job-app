# 🚀 LinkedIn Auto Job Application Dashboard

An automated, AI-powered job application system built with **Python**, **Gradio**, and **Google Gemini Flash**. This dashboard allows you to upload your resume and a screenshot of a LinkedIn job post, extracts recruiter contact details via AI, drafts a tailored cover letter, and automatically dispatches your application via SMTP with your PDF resume attached.

---

## ✨ Features

- **AI-Powered Extraction (OCR):** Automatically scans LinkedIn job post screenshots to extract HR/recruiter email addresses and job titles using Google Gemini.
- **Tailored Cover Letter Generation:** Generates professional application text highlighting your engineering background and technical competencies.
- **Automated Resume Attachment:** Automatically attaches your custom PDF CV (`Umair_CV.pdf`) to outgoing emails.
- **Interactive Web Interface:** Built using **Gradio** with custom styling for real-time tracking, clean inputs, and instant response feedback.
- **Secure Authentication:** Supports secure login using Google Colab Secrets or manual input fields for safe credential handling.

---

## 🛠️ Tech Stack & Requirements

- **Language:** Python 3.10+
- **Framework & UI:** `gradio`
- **AI Model:** Google Gemini (`google-genai`, `gemini-3.8-flash`)
- **Image Processing:** `pillow`
- **Email Dispatch:** `smtplib`, `email.mime`

---

## 🚀 Installation & Setup

### 1. Clone or Open in Google Colab
You can run this project directly inside **Google Colab** or locally on your machine.

### 2. Install Required Libraries
Run the following command to install the required dependencies:
```bash
pip install google-genai pillow gradio
