# 📊 AI-powered Document Intelligence & Agentic AI Solutions
🚀 Projects built during my internship at **L&T Chennai – Information Systems Department (ISD)**  
📅 Duration: May 19, 2025 – July 9, 2025

---

## 📌 Overview
During my internship, I developed and deployed end-to-end AI pipelines for:
- Automated document content extraction (text, tables, images)
- OCR systems for scanned & handwritten documents
- Cheque vs. non-cheque image classification
- Keyword-based Q&A on handwritten documents
- **Agentic AI** solution for intelligent helmet detection in construction images

These projects were built using deep learning, vision-language models, and served with **FastAPI** & **Streamlit** for real-time interaction.

---

## 🧩 Projects & Key Features

### 📄 1. Automated PDF Content Extraction
- Extract text using `pdfplumber`
- Parse tables with `camelot`
- Extract images via `PyMuPDF`
- Save structured outputs for analytics

---

### ✍️ 2. OCR & Handwritten Text Recognition
- Explored multiple OCR frameworks: **DocTR**, **Donut**, **PaddleOCR**, **Tesseract**, **TrOCR**, **CalamariOCR**
- Built APIs and UIs to visualize extracted content and confidence scores

---

### 🧾 3. Cheque Image Classifier
- Used **MobileNetV2** CNN for lightweight binary classification (cheque / non-cheque)
- Deployed with **FastAPI** backend and **Streamlit** UI

---

### 🔍 4. Keyword-based Handwritten Document Q&A
- Used **Donut (Document Understanding Transformer)** fine-tuned on DocVQA
- Users can upload handwritten docs and ask natural language questions like:
  - *“What is the Invoice Number?”*
- Real-time results via Streamlit frontend

---

### 🪖 5. Agentic AI: Intelligent Helmet Detection
- Vision-language detection using **GroundingDINO**
- Precise mask segmentation via **Segment Anything Model (SAM)**
- Prompt-driven detection (e.g., “person wearing helmet”)
- Visualize bounding boxes & masks; designed for safety compliance monitoring

---

## ⚙️ Tech Stack
- Python
- FastAPI (API backend)
- Streamlit (interactive UI)
- Deep Learning models: MobileNetV2, Donut, DocTR, GroundingDINO, SAM
- Libraries: pdfplumber, camelot, PyMuPDF, PaddleOCR, OpenCV, transformers

---

## 📂 Folder Structure
