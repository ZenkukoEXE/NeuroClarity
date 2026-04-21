# NeuroClarity: Academic Brief Simplifier

A Streamlit web application that simplifies complex academic language in briefs and provides time management estimates.

## Features

- Upload PDF, DOCX, or TXT files
- Simplify complex vocabulary using NLTK thesaurus
- Estimate reading/writing time for each section
- Customize total assignment time
- Download simplified brief as DOCX

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/NeuroClarity-FYP-Application.git
   cd NeuroClarity-FYP-Application
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

The app will open in your default web browser.

## Requirements

- Python 3.7+
- Internet connection (for NLTK data download on first run)

## Usage

1. Upload your academic brief file
2. Adjust the total time allocation if needed
3. View the simplified sections with time estimates
4. Download the processed document

## Deployment

This app can be deployed to:
- Streamlit Cloud
- Heroku
- Any platform supporting Python/Streamlit apps

For Streamlit Cloud deployment, push to GitHub and connect your repository.