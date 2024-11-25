# Smart ATS Resume Tracker Using Gemini AI

A Smart ATS (Applicant Tracking System) Resume Tracker that uses Google's Gemini AI model to evaluate and analyze resumes against job descriptions. The application provides feedback on the resume’s strengths, areas for improvement, and keyword analysis to help candidates optimize their resumes for better matching with job roles.

---

## Features

- **Resume Evaluation**: Analyzes resumes against job descriptions and provides detailed insights on strengths and weaknesses.
- **Skill Improvement Suggestions**: Provides recommendations on areas where candidates can improve their skills to better align with the job requirements.
- **Keyword Analysis**: Identifies missing keywords that are important for Applicant Tracking Systems (ATS), improving the chances of the resume being shortlisted.
- **Match Percentage**: Calculates the match percentage between the uploaded resume and the job description, followed by suggestions for improvement.
- **Query-Based Feedback**: Allows users to ask specific questions regarding their resumes and get personalized answers.

---

## SMART ATS RESUME TRACKER USING LLM



## Technologies Used

- **Streamlit**: A Python framework for building interactive web applications, used for the frontend.
- **Google Generative AI (Gemini)**: Used for generating AI-powered content to analyze and review resumes.
- **PyMuPDF (fitz)**: A library to extract text from PDF files, enabling the analysis of resumes in PDF format.
- **PIL (Pillow)**: A Python Imaging Library for image processing (not used in current version, but imported for potential future features).
- **dotenv**: Used to manage environment variables securely, particularly for storing the Google API key.
- **os**: Standard Python library for interacting with the operating system, used to read environment variables.

---

## Installation

1. Clone the repository:
   git clone https://github.com/yourusername/ats-resume-tracker.git

2. Navigate to the project directory:
   cd ats-resume-tracker

3.Install the required dependencies:
   pip install -r requirements.txt

4. Create a .env file in the root directory and add your Google API key:
   GOOGLE_API_KEY=your_google_api_key_here

5. Run the Streamlit app:
   streamlit run app.py

---

## Usage

1. Upload a resume (PDF format).
2. Enter the job description you want to match the resume against.
3.Use the provided buttons to:
  -Tell Me About the Resume: Get a professional evaluation of the resume.
  -How Can I Improve My Skills: Receive skill improvement suggestions based on the job     description.
  -What Are the Missing Keywords: Identify missing keywords from the resume.
  -Percentage Match: Get the match percentage between the resume and the job description.
  -Answer My Query: Ask specific questions and get tailored feedback from the AI.

  
