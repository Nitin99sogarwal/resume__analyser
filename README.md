# resume__analyser
Application Tracking System (ATS) 💻
This is a web application designed to evaluate resumes based on given job descriptions. The app helps job seekers improve their resumes by providing a match percentage, missing keywords, and a profile summary. The application leverages Streamlit for the front end, PyPDF2 for reading PDF files, and Google's Generative AI for generating responses.

Features
Upload your resume in PDF format.
Input job descriptions for comparison.
Get a detailed evaluation of your resume, including:
Job Description Match Percentage
Missing Keywords
Profile Summary
Technologies Used
Streamlit: For creating the web application interface.
PyPDF2: For extracting text from PDF resumes.
Google Generative AI: For analyzing resumes and job descriptions.
dotenv: For loading environment variables.
Prerequisites
Python 3.7 or higher
Streamlit
PyPDF2
python-dotenv
google-generativeai
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-repository/ats.git
cd ats
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Set up your Google API key:

Create a .env file in the project root directory.
Add your Google API key to the .env file:
makefile
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open your web browser and go to http://localhost:8501 to use the application.

Input the job description and upload your resume in PDF format.

Click the "Submit 🚀" button to get the evaluation.

Code Overview
app.py: Main file containing the Streamlit app code.
.env: File to store environment variables.
requirements.txt: File listing all the required Python packages.
License
This project is licensed under the MIT License. See the LICENSE file for more details.
