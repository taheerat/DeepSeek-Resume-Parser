# DeepSeek-Resume-Parser
DeepSeek OCR + Gemini agent to extract structured resume fields as JSON.

This project combines DeepSeek OCR and Google Gemini through an Agno agent to automatically extract and structure resume data from images.
It performs OCR (Optical Character Recognition) on the first page of a resume image using DeepSeek, 
then passes the extracted text to a Gemini-powered agent to parse key resume fields into a clean JSON format.

⚙️ Tech Stack:
Google Colab — Easy setup with GPU acceleration

DeepSeek-OCR — Text extraction from resume images

Google Gemini API (via Agno) — Natural language understanding and structured parsing

Python & Transformers — Model integration and executio
