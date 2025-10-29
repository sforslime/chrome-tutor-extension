# 🌐 Universal Research Companion (Multimodal Edition)

### “Read, Understand, and Learn — from any webpage, document, or screenshot — all offline, powered by Chrome’s built-in AI.”

---

## 🧠 Overview

**Universal Research Companion** is a Chrome Extension and Web App that helps students, researchers, and knowledge workers instantly understand and organize information — whether it comes from web pages, PDFs, or even screenshots of lecture slides.

It uses Google Chrome’s **built-in AI APIs** (powered by Gemini Nano) to **summarize**, **rewrite**, **translate**, and **proofread** content locally on your device.  
With multimodal support, it can even **analyze images**, such as lecture slides or infographics, to extract and summarize their content.

No cloud servers, no privacy risks — just fast, local AI assistance directly in your browser.

---

## 🚀 Key Features

| Feature | Description | API Used |
|----------|--------------|----------|
| 🖼️ **Slide Analyzer** | Upload screenshots or slides — the AI extracts text and key ideas from each image. | Prompt API (multimodal) |
| 📰 **Page Summarizer** | Summarize any webpage or PDF in one click. | Summarizer API |
| ✏️ **Smart Writer** | Generate abstracts or concise study notes from content. | Writer API |
| 🪄 **Rewriter & Simplifier** | Instantly simplify, rephrase, or enhance any text. | Rewriter API |
| ✅ **Proofreader** | Fix grammar and clarity issues in your notes. | Proofreader API |
| 🌍 **Translator** | Translate text or summaries into your preferred language. | Translator API |
| 🧩 **Flashcard Generator** *(optional)* | Convert summarized notes into study flashcards or quiz questions. | Writer API |

---

## 💡 Problem Statement

Students and professionals often work with **unstructured study materials** — long articles, lecture slides, screenshots, and PDFs — making it time-consuming to extract useful information.  
Existing tools rely on cloud AI, raising privacy concerns and requiring constant internet connectivity.

The **Universal Research Companion** solves this by running **entirely on-device** using Chrome’s built-in AI models.  
It allows users to read and learn efficiently — **offline, privately, and instantly.**

---

## 🧩 APIs Used

- **Prompt API (Multimodal)** – to analyze and extract information from screenshots or images.
- **Summarizer API** – to condense large blocks of text into key points.
- **Writer API** – to create original summaries or study notes.
- **Rewriter API** – to simplify or rephrase content.
- **Proofreader API** – to correct grammar and polish writing.
- **Translator API** – to add multilingual support.

---

## 🖥️ Tech Stack

**Frontend:**  
- React + Tailwind CSS (Extension UI)  
- Chrome Manifest V3  

**Backend / AI Integration:**  
- Chrome Built-In AI APIs (client-side)  
- Optional: Firebase AI Logic (for hybrid cloud fallback)  

**Storage:**  
- IndexedDB (local cache and notes)  

---
