# Smart ATS

Smart ATS is a Streamlit app designed to improve your resume by evaluating it against job descriptions using the Google Gemini API.

## Features

- Upload a PDF resume
- Paste a job description
- Analyze and get suggestions on how to improve your resume based on the job description

## Requirements

- Python 3.7 or higher
- Streamlit
- google-generativeai
- PyPDF2
- python-dotenv

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ad/smart-ats.git](https://github.com/Adeel-Farooq-Khan/ATS_Tracker_Using_Gemini_API
   cd ATS_Tracker_Using_Gemini_API
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the root directory and add your Google API key:

   ```env
   GOOGLE_API_KEY=your_google_api_key_here
   ```

5. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Usage

1. Open the app in your browser.
2. Paste the job description into the "Paste the Job Description" text area.
3. Upload your resume in PDF format.
4. Click "Submit" to get suggestions for improving your resume.


## Acknowledgements

- Google Gemini API
- Streamlit
- PyPDF2
```

Feel free to customize these as needed!
