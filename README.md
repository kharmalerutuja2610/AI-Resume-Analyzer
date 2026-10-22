AI Resume Analyzer 🤖

1. Project Overview

AI Resume Analyzer is a Python-based web application developed using Streamlit. It allows users to upload their resumes in PDF format and extracts text from the uploaded files.

The application displays the extracted resume content on the screen, making it easier for users to view the information contained in their resumes.

2. Technologies Used

1. Python
Python is used to write the application logic and process the uploaded resume.

2. Streamlit
Streamlit is used to create a simple and interactive web interface for uploading resumes and displaying their content.

3. pdfplumber
pdfplumber is a Python library used to extract text from PDF files.

3. How Does It Work?

The application works through the following steps:

1. The application displays the title "AI Resume Analyzer".
2. A welcome message appears on the screen.
3. The user uploads a resume in PDF format.
4. The application displays a success message when a file is uploaded.
5. The pdfplumber library opens the uploaded PDF file.
6. The application extracts text from each page of the PDF.
7. The extracted text is displayed on the screen using Streamlit.

4. Example

Input:

The user uploads a resume in PDF format containing information such as:

- Name
- Education
- Technical Skills
- Projects
- Work Experience

Process:

The application reads the uploaded PDF and extracts its text.

Output:

The extracted resume text is displayed on the application screen.

For example, if the resume contains the skills Python, SQL, and Power BI, the application displays these details as part of the extracted text.

5. Purpose of the Project

The main purpose of this project is to simplify the process of accessing information from PDF resumes.

It provides a simple interface where users can upload a resume and view its extracted text without manually copying the content from the PDF.

6. Key Features

- Simple and user-friendly interface.
- Upload resumes in PDF format.
- Display a success message after uploading.
- Extract text from PDF resumes.
- Process text from multiple pages.
- Display extracted resume content on the screen.

7. Future Enhancements

The project can be improved by adding the following features:

- Automatic skill identification.
- Job description and resume matching.
- Resume scoring system.
- Missing keyword detection.
- AI-based resume feedback.

These features can be implemented in future versions.

8. Author

Name: Rutuja Kharmale

Developed an AI-powered Resume Analyzer using Python, Flask, NLP, and Machine Learning. The system extracts text from resumes, identifies skills, compares resumes with job descriptions, and generates a match score to assist recruiters in candidate screening.
