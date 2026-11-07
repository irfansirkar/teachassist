# TeachAssist

An AI study co-pilot: chat with your notes, read handwritten pages and generate practice tests.

**Live demo:** https://irfansirkar.github.io/teachassist/

Built by **Mohammad Irfan Sirkar** for **SMC Expogenix and AWS Cloud events (2025)**.

## What the project does

Students upload PDFs and documents. TeachAssist answers questions using retrieval-augmented generation (RAG) and cites the pages it used. It reads handwritten notes with OCR and generates multiple-choice practice tests with explanations.

## Original stack

- Gemini
- LangChain (RAG)
- PyPDF2
- OCR
- Streamlit

## About this repository

This repository holds an interactive demo of the project. The demo runs entirely in the browser on GitHub Pages and uses built-in sample data, so it never needs a server, a GPU or an API key.

The demo includes a 5-page sample document on photosynthesis. The chat matches questions to those pages and cites them. The OCR tab reads a sample handwritten note, and the practice test is a real 5-question quiz with scoring.

The original project code is not included here.

## Run the demo locally

Open `index.html` in any browser. There is no build step.

## More projects

See the full portfolio at https://irfansirkar.github.io/PERSONAL-PORFOLIO-WEBSITE/
