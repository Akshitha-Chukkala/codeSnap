# CodeSnap 💻

CodeSnap is an AI-powered coding learning assistant built with Streamlit. It helps beginner and intermediate coding learners understand code by uploading screenshots or entering code and asking questions.

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