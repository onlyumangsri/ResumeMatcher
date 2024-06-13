# Resume Matcher

A web application that matches job descriptions with resumes to find the most relevant candidates based on text similarity.

## Features

- Upload multiple resumes in PDF, DOCX, or TXT formats.
- Input a job description.
- Match resumes to the job description using cosine similarity.
- Display the top matching resumes with similarity scores.

## Requirements

- Python 3.x
- Flask
- docx2txt
- PyPDF2
- scikit-learn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/resume-matcher.git
    cd resume-matcher
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Create the `uploads` directory:
    ```bash
    mkdir uploads
    ```

## Usage

1. Run the application:
    ```bash
    python main.py
    ```

2. Open a web browser and navigate to:
    ```
    http://localhost:5000
    ```

3. Enter the job description and upload the resumes, then click "Match Resume(s)".
