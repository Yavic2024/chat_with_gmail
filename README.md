# Chat with Gmail

Interact with your Gmail inbox using AI! This project allows you to ask questions about your emails and get intelligent answers using Retrieval Augmented Generation (RAG) and OpenAI's GPT models.

## Features

- Connects securely to your Gmail account
- Uses RAG to answer questions based on your email content
- Powered by OpenAI GPT-4 Turbo and Chroma vector database
- Simple Streamlit web interface

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Yavic2024/chat_with_gmail.git
   cd chat_with_gmail
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Gmail API credentials**
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project and enable the Gmail API.
   - Configure OAuth consent and download `credentials.json` to this folder.

4. **Get your OpenAI API key**
   - Sign up at [OpenAI](https://platform.openai.com/) and create an API key.

5. **Run the app**
   ```bash
   streamlit run chat_gmail.py
   ```

## Usage

- Enter your OpenAI API key in the app.
- Authorize Gmail access when prompted.
- Ask questions about your emails in the chat interface.

## File Overview

- `chat_gmail.py` — Main Streamlit app
- `requirements.txt` — Python dependencies
- `README.md` — Project documentation

---

**Author:** [Yavic2024](https://github.com/Yavic2024)
