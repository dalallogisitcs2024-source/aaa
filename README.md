# 📚 AI-Powered Smart Study Assistant

An all-in-one AI-powered academic platform designed specifically for university and school students. It supports comprehensive file formats (**PDF, Excel, Access, PowerPoint, Word, and Images**) to handle homework, textbook indexing (RAG), smart search, and professor lecture notes tracking.

---

## 🚀 Core Features

1. **📚 Universal Document Library & RAG:** Upload textbooks, slides, and reference materials across multiple formats (`.pdf`, `.pptx`, `.docx`), which are automatically processed and stored for precise context-aware AI retrieval.
2. **✍️ Multi-Format AI Assignment Solver:** Upload homework files in any format—including Excel (`.xlsx`), Access (`.accdb`), Word (`.docx`), PDF, or Images of handwritten questions—and get step-by-step solutions strictly based on your course material.
3. **🔍 Smart Search & Instant Summarizer:** Search for any concept or formula across all uploaded materials instantly, or generate chapter summaries with a single click.
4. **🎯 Professor Notes Tracker:** Log daily notes and exam tips emphasized by professors during lectures and automatically link them to the relevant course content.

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express, TypeScript
* **Database & ORM:** PostgreSQL (with `pgvector` support), Drizzle ORM
* **AI & Parsing:** Multi-format parsers (PDF, Office documents, Images/OCR) and custom Vector Embeddings for RAG.
