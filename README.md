# Developing an LLM Based Phishing Detection System for Email Security
GPT-4 based phishing email detection system built with Python and Gradio for analyzing and classifying suspicious emails.

## Features
- AI-powered phishing detection using GPT-4
- Phishing risk scoring (0%–100%)
- Email classification: Legitimate / Suspicious / Phishing
- Explanation of detection results
- User login and registration system
- Admin panel to view user reports
- Scan history tracking
- Feedback/report submission system
- Gradio web interface

## How It Works
The system sends email content to GPT-4 using prompt engineering. The model evaluates phishing indicators such as urgency, suspicious links, grammar issues, and requests for sensitive data, then returns a risk score and reasoning.

## Tech Stack
- Python
- OpenAI GPT-4 API
- Gradio
- Regex
