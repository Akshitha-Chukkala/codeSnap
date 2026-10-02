# CodeSnap 💻

CodeSnap is an AI-powered coding learning assistant built with Streamlit. It helps beginner and intermediate coding learners understand code by uploading screenshots or entering code and asking follow-up questions.

## What CodeSnap Does

- **Screenshot & Code Analysis**: Upload images of code or paste snippets for automated analysis.
- **AI-Powered Explanations**: Generates step-by-step, beginner-friendly code breakdowns using the Google Gemini API.
- **Error Identification**: Spotlights errors, explains why they happen, and provides recommended fixes.
- **Interactive Q&A**: Allows users to ask follow-up questions about concepts and programming languages.
- **Session Summaries**: Summarizes learning sessions and delivers summary notes directly via Gmail.

## Features

- Upload screenshots of code for analysis
- Paste code and ask questions
- AI-powered code explanations using Google Gemini
- Step-by-step beginner-friendly explanations
- Identifies programming languages and important concepts
- Explains visible errors and possible fixes
- Ask follow-up questions
- Generate a summary of the learning session
- Send the learning summary via email

## Technologies Used

- Python
- Streamlit
- Google Gemini API
- Google Gen AI SDK
- smtplib (Gmail Integration)

## Project Structure

```text
codeSnap/
├── __pycache__/
├── .streamlit/
│   └── secrets.toml
├── venv/
├── .gitignore
├── app.py
├── prompts.py
├── README.md
└── requirements.txt

## How to Run Locally

1. **Clone the Repository**

   ```bash
   git clone [https://github.com/YOUR_USERNAME/codeSnap.git](https://github.com/YOUR_USERNAME/codeSnap.git)
   cd codeSnap

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt

3. **Configure Secrets**

   Create a .streamlit/secrets.toml file in the root folder with your API credentials:

   ```toml
   GMAIL_ADDRESS = "your_email@gmail.com"
   GMAIL_APP_PASSWORD = "your_app_password"
   GEMINI_API_KEY = "your_gemini_api_key"

4. **Launch the App**

   ```bash
   streamlit run app.py