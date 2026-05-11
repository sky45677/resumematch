# ResumeMatch AI

A real-time resume screener and job matcher that uses AI to analyze resumes against job descriptions, provide match scores, identify missing keywords, suggest improvements, and rewrite resumes for better matching.

![ResumeMatch AI Screenshot](screenshot.png) <!-- Add your screenshot here -->

## Features

- **Resume Upload & Parsing**: Accept PDF and DOCX files, extract text using PyMuPDF and python-docx
- **Semantic Match Scoring**: Calculate cosine similarity using sentence-transformers (all-MiniLM-L6-v2)
- **Keyword Gap Analysis**: Identify missing keywords using spaCy (en_core_web_lg)
- **Improvement Suggestions**: Rule-based engine for resume enhancement tips
- **AI Resume Rewriter**: Rewrite resumes to better match job descriptions using Hugging Face Inference API
- **Scan History**: View past scans with job titles, scores, and dates
- **User Authentication**: Secure login/register system
- **Real-time UI Feedback**: Animated score circle, keyword badges, and suggestions

## Tech Stack

![Django](https://img.shields.io/badge/Django-4.2-%23092E20?logo=django)
![DRF](https://img.shields.io/badge/Django%20REST%20Framework-3.15-%23EF1123?logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13-%234169E1?logo=postgresql)
![Celery](https://img.shields.io/badge/Celery-5.4-%2337814A?logo=celery)
![Redis](https://img.shields.io/badge/Redis-5.0-%23DD0031?logo=redis)
![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-2.7-%23F97316?logo=huggingface)
![spaCy](https://img.shields.io/badge/spaCy-3.7-%2309A3D5?logo=spacy)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-1.24-%231D3557?logo=python)
![python-docx](https://img.shields.io/badge/python--docx-1.1-%232A52BE?logo=microsoft)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4-%2306B6D4?logo=tailwindcss)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Inference-%23FFD21E?logo=huggingface)

## Setup Instructions

### Prerequisites

- Python 3.11+
- PostgreSQL
- Redis
- Git

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/resumematch-ai.git
   cd resumematch-ai
