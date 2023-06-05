# PDF-QA

PDF-QA is a web-based application that allows users to extract insights from PDF documents by asking questions. The application leverages the power of Langchain, Streamlit, and OpenAI to provide an intuitive and interactive platform for extracting valuable information from PDFs.

## Features

- Upload PDF files: Users can easily upload PDF files through the user-friendly interface.
- Ask questions: Users can enter their questions related to the content of the PDF documents.
- PDF text extraction: The application automatically extracts the text content from the uploaded PDF files.
- Question answering: The extracted text is processed using OpenAI's advanced language models to provide accurate answers to user queries.
- Display of answers: The application presents the answers to user questions in a user-friendly interface.
- Dark theme and modern UI: The application features a visually appealing dark theme and modern user interface.

## Technologies Used

- Python
- Langchain
- Streamlit
- OpenAI

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/your-username/pdf-qa.git
   ```

2. Install the dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the application:

   ```
   streamlit run app.py
   ```

4. Open your web browser and navigate to `http://localhost:8501` to access the PDF-QA application.

## Usage

1. Upload a PDF file by clicking on the "Upload PDF" button and selecting the desired file.
2. Enter your question in the "Enter your question" input field.
3. Click the "Submit" button to submit your question.
4. The application will process the PDF and provide the answer to your question.
5. The answer will be displayed in the "Answer" section of the interface.
