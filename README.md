# Automated Resume Scanner

The **Automated Resume Scanner** is a web-based application that streamlines the process of evaluating and ranking resumes against job descriptions using machine learning. Built with Java (Spring Boot) for backend services and Python (Flask) for machine learning, it automates the extraction and comparison of resume content to identify the best candidates for a given role.

## Key Features:
- Upload resumes in multiple formats (PDF, DOCX).
- Extract and parse resume data using Apache Tika.
- Store resumes and job descriptions in a MySQL database.
- Compare resumes against job descriptions using TF-IDF and cosine similarity algorithms.
- Rank resumes based on relevance to the job description.
- Simple frontend interface to view ranked resumes.

## Tech Stack:
- **Backend:** Java (Spring Boot), MySQL
- **Machine Learning:** Python (Flask, scikit-learn)
- **Frontend:** HTML, CSS, JavaScript
- **Containerization:** Docker

This project automates the initial screening process for recruiters, saving time and effort by filtering and ranking resumes efficiently.

