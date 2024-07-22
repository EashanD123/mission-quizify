# Project Title

## Description
The mission quizify project consists of an AI quiz builder that uses various technologies: Google Gemini and Vertex AI API are used for document processing and quiz generation, 
embeddings and Langchain are used for creating text embeddings, Google Service Account is used for authentication, PDF loader is used for document ingestion, and Streamlit is used 
for building the frontend user interface. This project, provided by Radical AI, generates quizzes based on user-provided documents and topics by analyzing the PDF documents and 
breaking them down to create multiple-choice questions.

## Table of Contents
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Usage

To run the Quiz Builder:

1. Clone this mission-quizify repository
2. Install the required dependencies from the `requirements.txt` file by executing the command `pip install -r requirements.txt`.
3. Change the directory by executing `tasks/task_[name of task]`. task_10.py has the full implementation of the AI quiz builder
4. Run the Streamlit application by executing `streamlit run [name of task].py` in the terminal where xxx is the name of the py file you want to run.
5. Follow the instructions provided in the user interface to interact with the quiz builder.

## Acknowledgments

This project is based on [mission-quizify](https://github.com/radicalxdev/mission-quizify) and developed by radicalxdev. 

- [Radical AI](https://www.radicalai.org/)
- [Google Cloud Platform](https://cloud.google.com/)
- [Langchain](https://langchain.com/)
- [Streamlit](https://streamlit.io/)

## License

This project is licensed under the MIT License. Check out the LICENSE file for details.
