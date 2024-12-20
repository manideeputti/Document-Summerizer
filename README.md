# Document Summarizer

Document Summarizer is a web application that leverages FastAPI, Google Generative AI, and other libraries to perform instant document summarization. Users can upload PDF, DOCX, or TXT files, and the application generates a simplified summary with clear headings.

---

## Features
- **Multi-format Support**: Handles PDF, DOCX, and plain text files.
- **AI-Powered Summarization**: Utilizes Google Generative AI (Gemini-1.5 Flash) for high-quality document summaries.
- **Responsive Web Interface**: User-friendly design with instant feedback.
- **Customizable Backend**: Built using FastAPI for speed and flexibility.

---

## Technologies Used
- **Backend**: FastAPI, Python
- **Frontend**: HTML, CSS, Jinja2
- **AI Integration**: Google Generative AI (`google.generativeai`)
- **File Handling**: PyPDF2, python-docx, Pillow
- **Web Server**: Uvicorn

---

## Installation

### Prerequisites
1. Python 3.8+
2. Google API key for Generative AI integration

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/document-summarizer.git
   cd document-summarizer
Create a virtual environment:
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Set up the Google Generative AI API key in your environment:
bash
Copy code
export GOOGLE_API_KEY="your_google_api_key"  # For Linux/Mac
set GOOGLE_API_KEY="your_google_api_key"    # For Windows
Running the Application
Start the FastAPI application:
bash
Copy code
uvicorn main:app --reload
Open your browser and navigate to:
arduino
Copy code
http://127.0.0.1:8000
Usage
On the homepage, upload a document in PDF, DOCX, or TXT format.
Click the "Summarize" button.
View the summarized text with headings on the results page.
File Structure
document-summarizer/
├── main.py               # Main application script
├── templates/            # HTML templates for the frontend
│   ├── index.html        # Homepage
│   ├── result.html       # Results page
├── static/               # Static files (CSS, JS)
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
Dependencies
FastAPI: Web framework for the backend
python-multipart: File uploads
Uvicorn: ASGI server
PyPDF2: PDF file text extraction
python-docx: DOCX file text extraction
google.generativeai: Integration with Google Generative AI
Pillow: Image file handling
Jinja2: Templating engine for dynamic HTML generation

Contribution
Feel free to fork this repository and submit pull requests. Contributions, issues, and feature requests are welcome!

Contact
If you have any questions or suggestions, please reach out to:

Email_id: umdn1030@gmail.com
