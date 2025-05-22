# Resumetrics

An **AI-powered Application Tracking System platform** that allows users to upload their resumes and match them with job descriptions using intelligent backend processing.

## Overview

This project is a resume-job matcher tool built using a modern full-stack architecture. It provides a seamless interface for users to upload resumes, and the backend handles parsing and comparison with job descriptions to assist in recruitment or self-assessment.

## Features

- **Resume Parsing**: Upload resumes in PDF, DOCX, or TXT formats. The text content is extracted and parsed.
- **Job Description Input**: Enter or paste the job description for a specific role.
- **Resume Matching**: Uses Gemini API to evaluate alignment between resume and job description.
- **Percentage Match**: Displays how well the resume fits the job using a percentage score.
- **Missing Keywords**: Lists critical job keywords that are missing from the resume.
- **Profile Summary**: Generates a concise summary of the candidate's skills and fit.
- **Visual Representation**: Displays a pie chart visualizing the percentage match.

## Requirements

### Backend
- Python 3.9+
- FastAPI
- Uvicorn
- python-multipart
- Google Gemini API
- python-docx
- PyMuPDF or similar for PDF parsing

Install backend dependencies:
```bash
pip install -r requirements.txt
```

## 🛠 Tech Stack
### Frontend
- **Next.js**: For building the user interface and routing.
- **React**: Component-based frontend library.
- **JavaScript / TypeScript**: For interactive logic.
- **FormData API**: For handling file uploads.

### Backend
- **FastAPI**: High-performance Python framework used to build RESTful APIs.
- **Uvicorn**: ASGI server to run the FastAPI application.
- **Python-Multipart**: Handles file uploads in FastAPI.

### Communication
- **REST API**: Frontend communicates with backend via HTTP POST requests.
- **CORS**: Configured to allow cross-origin requests from frontend to backend.
