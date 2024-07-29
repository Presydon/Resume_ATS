# Resume Applicant Tracking System

This project is a Resume Applicant Tracking System (ATS) built using Streamlit. The system allows users to upload resumes, paste job descriptions, and generate cover letters. It leverages Google's Generative AI to provide insightful feedback and suggestions for improving resumes based on the job description provided.

## Table of Contents

  Features
  Installation
  Usage
  Project Structure
  Technologies Used
  License

### Features

Resume Upload: Upload your resume in PDF format.
Job Description Input: Paste the job description directly in the sidebar.
AI-Powered Feedback: Get detailed feedback on your resume's alignment with the job description.
Cover Letter Generation: Automatically generate a cover letter tailored to the job description.
Job Description Match Percentage: Provides a percentage that matches the resume to the job description.
Interactive Sidebar: Easy navigation with options to generate cover letters and view social media links.
Custom Styling: Enhanced user experience with custom CSS for better UI design.

### Prerequisites

Python 3.11 or higher
Pip (Python package installer)
Clone the repository: git clone https://github.com/Presydon/resume-ats.git
Navigate to the project directory: cd resume-ats
Create and activate a virtual environment: python -m venv venv
Install the required dependencies: source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the necessary dependencies: pip install -r requirements.txt

### Usage

Run the Streamlit app: streamlit run app.py
Open your web browser and go to the URL provided by Streamlit (usually http://localhost:8501).
Use the sidebar to upload your resume and paste the job description.
Click on the "Generate Cover Letter" button to get a tailored cover letter.

### Project Structure

resume-ats/
│
├── app.py                   # Main application file
├── application.py           # Core functions and logic
├── style.css                # Custom CSS for styling
├── README.md                # Project README file
├── requirements.txt         # Python dependencies
├── assets/
│   ├── logo.png             # Project logo
│
└── venv/                    # Virtual environment directory

### Technologies Used

Streamlit: For building the web application.
PyPDF2: For extracting text from PDF resumes.
Google Generative AI: For generating AI-powered feedback and cover letters.
Python-Docx: For creating and downloading cover letters in Word format.
Custom CSS: For enhancing the UI design.

### Contact
Built by Precious Victor. Connect with me on LinkedIn and Twitter.
