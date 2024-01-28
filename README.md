# Resume Refiner App

This is a resume refiner app built using Gemini Pro and Streamlit. The app takes a job description (JD) and a resume as input, and outputs information including JD Match percentage, Missing Keywords, Profile Summary, and Suggestions.

## Live Link
[Live Link](https://resumerefiner.streamlit.app/)

## Requirements
- Streamlit
- PyPDF2
- google.generativeai
- python-dotenv

## Installation
1. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run your_app_name.py
   ```
2. Open the app in your browser and paste the job description (JD).
3. Upload your resume in PDF format.
4. Click the "Submit" button to get the refined resume analysis.

