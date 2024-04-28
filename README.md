# Chat with PDF using Gemini 💬📄

This Streamlit application allows users to ask questions based on uploaded PDF files and receive AI-generated replies using the Gemini conversational AI model.

## Features

- **PDF Upload:** Users can upload one or more PDF files containing textual content.
- **Ask Questions:** Users can type a question related to the content of the uploaded PDF files.
- **AI Response:** The application processes the uploaded PDF files, generates AI embeddings, and uses the Gemini model to provide responses to user questions based on the content.

## Technologies Used

- Streamlit: Front-end framework for building interactive web applications with Python.
- PyPDF2: Library for extracting text from PDF files.
- Google Generative AI: Utilized for embeddings and conversational AI capabilities.
- FAISS: Vector index library for efficient similarity search.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository.

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Set up the environment variables:
   - Create a .env file in the project root directory.
   - Add your Google API key to the .env file:
    ```bash
    GOOGLE_API_KEY=your_google_api_key_here

4. Run the Streamlit application:
   ```bash
   streamlit run app.py

5. Access the application in your web browser at `http://localhost:8501`

## Usage
1. Upload one or more PDF files using the file uploader in the sidebar.
2. Type a question related to the content of the uploaded PDF files in the text input field.
3. Click the "Submit & Process" button to process the PDF files and generate AI embeddings.
4. After processing completes, click the "Get Reply" button to receive an AI-generated response to your question.

