# YTtranscriber

# 📄 YouTube Transcript to Detailed Notes Converter

This is a Streamlit web app that converts YouTube videos into summarized notes. It extracts the transcript from a given YouTube video (if captions are available), then uses Google Gemini Pro to generate a concise summary of the content in around 250 words.

---

## 🚀 Features

- ✅ Accepts any valid YouTube video link
- ✅ Extracts transcript from videos with captions
- ✅ Summarizes content using Gemini AI
- ✅ Outputs structured and readable bullet-point notes
- ✅ Displays the video thumbnail for context

---

## 📌 Requirements

- Python 3.10+
- Google API Key (for Gemini)
- Required Python libraries:
  - streamlit
  - youtube-transcript-api
  - python-dotenv
  - google-generativeai

---

## 🔧 Installation and Setup

1. **Clone the repository** or download the project files.

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
