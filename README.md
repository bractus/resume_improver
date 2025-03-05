# Resume Optimizer

This project uses AI to create an optimized resume that is both ATS-friendly and human-readable. It processes your input resume information and creates a well-structured, professional resume.

## Features

- Converts raw resume text into a well-structured format
- Optimizes content for ATS (Applicant Tracking Systems)
- Organizes information into clear sections (Professional Profile, Experience, Education, Skills)
- Supports multiple languages
- Creates output in Microsoft Word format

## Setup

1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Create a `.env` file with your API keys:
```
OPENAI_API_KEY=your_openai_api_key_here
OPENAI_MODEL_NAME=gpt-4-mini
SERPER_API_KEY=your_serper_api_key_here
```

## Usage

1. Place your resume information in a file named `resume.txt`
2. Run the script:
```bash
python extract.py
```
3. Find your optimized resume in `output.docx`

## Input Format

Place your resume information in `resume.txt` with your work experience, education, and skills. The AI will process and organize this information automatically.

## Output

The script generates an `output.docx` file containing your optimized resume with the following sections:
- Professional Profile
- Recent Experience
- Education
- Skills (including languages and technical skills)

## Requirements

- Python 3.7+
- OpenAI API key
- Serper API key
- Required Python packages (see requirements.txt) 