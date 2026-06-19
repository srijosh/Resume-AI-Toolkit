# Resume AI Toolkit

This repository contains a **Resume AI Toolkit** implemented in Streamlit. The app demonstrates how to build an AI-powered career assistant using `langchain-groq`, LangChain prompting, and PDF document processing.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Tools and Technologies](#tools-and-technologies)

## Introduction

The demo uses `app.py` to demonstrate:

- **Cover letter generation** with a Groq-backed LLM (`ChatGroq`)
- **Resume-to-job-description matching** with ATS and keyword analysis
- **Standalone resume evaluation** with structured feedback rubrics
- **Interactive career coaching chatbot** that understands resume context
- **PDF parsing pipeline** using LangChain document loaders
- **Streamlit-first workflow** for interactive experimentation and real-time AI responses

The app is designed for interactive use via Streamlit and includes four specialized tools for job hunters and career professionals.

## Features

- **Groq-powered model integration** using `langchain-groq` (Llama 3.3-70B-Versatile)
- **Streaming text generation** for responsive user experience
- **PDF resume parsing** with LangChain's `PyPDFLoader`
- **Session-persistent chatbot** with full conversation history
- **Structured evaluation prompts** with consistent scoring rubrics
- **Real-time response display** with markdown formatting

## Installation

1. Clone the repository:

```bash
git clone https://github.com/srijosh/Resume-AI-Toolkit.git
```

2. Navigate to the project folder:

```bash
cd Resume-AI-Toolkit
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set up environment variables by creating a `.env` file from `.env.sample`.

## Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

The app will open in your default browser. Choose from the four tools in the sidebar:

1. **✉️ Cover Letter Generator** — Generate tailored cover letters from resume + job description
2. **📊 Resume-JD Matcher** — Score resume against job description with detailed analysis
3. **🔍 Resume Checker** — Evaluate resume standalone for clarity, ATS compatibility, and skills
4. **💬 Career Coach Chat** — Chat with an AI mentor that knows your resume context

## Tools and Technologies

- **Streamlit**: Interactive web application framework
- **LangChain**: Orchestration, prompting, and document loading
- **langchain-groq**: Groq model integration for LangChain
- **GROQ Llama 3.3-70B-Versatile**: Large language model for content generation
- **PyPDF**: PDF resume parsing
- **LangChain Core**: Message types and prompt templates
- **python-dotenv**: Environment variable loading
