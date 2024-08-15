## Research Document Analyzer

Research Document Analyzer is a web application developed to streamline the process of understanding and extracting key insights from complex research papers. Whether you're a student, researcher, or professional, this tool provides an efficient way to summarize documents and answer specific questions based on their content.

## Features
Document Summarization: Automatically generate concise summaries of research papers, highlighting key points such as authorship, purpose, methodology, findings, and conclusions.
Q&A Functionality: Ask questions related to the content of research documents and receive accurate, context-driven answers.
File Support: Upload both PDF and DOCX files for analysis.
User Authentication: Secure user registration and login with JSON Web Tokens (JWT).
Frontend: Responsive user interface built with React.

## Architecture
This project consists of two main components:

Backend: Developed using Flask, it handles API requests, file processing, and interaction with MongoDB.

Frontend: Developed using React, it provides a user-friendly interface for uploading documents, viewing summaries, and asking questions.

## Getting Started
### Prerequisites
Ensure you have the following installed:

Python 3.8 or higher

MongoDB: To store users and document data.

OpenAI API Key: For accessing the GPT models.

Hugging Face Transformers: For T5 and BERT models.

### Installation
1. Clone the Repository:

   git clone https://github.com/yourusername/research-document-analyzer.git

   cd research-document-analyzer

3. Set Up a Virtual Environment:

   python3 -m venv venv

   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`

4. Install Dependencies:
   pip install -r requirements.txt

5. Configure Environment Variables:

   Create a .env file in the root directory and add the following:
   OPENAI_API_KEY=your_openai_api_key

   MONGODB_URL=your_mongodb_connection_string

7. Run the Application:

   Start the Flask server:
   python app.py

   The backend will be available at http://127.0.0.1:5000/.

## Frontend Setup

1. Navigate to the Frontend Directory:
   cd ../frontend

3. Install Dependencies:
   Install all required npm packages:
   npm install

5. Run the Frontend Development Server:
   Start the React development server:
   npm start

   The frontend will be available at http://127.0.0.1:3000/.












