# Resume-Parser-using-Transformers-based-Named-Entity-Recognition

## Objective:
This project is an NLP-based automation system that extracts structured information (Name, Skills, Degree, Institutions, Work Experience, etc.) from raw resumes in .txt or .pdf formats using transformer-based NER models from Hugging Face. Built for real-world HR automation tasks such as resume screening and shortlisting.

## Usecase:
Simulates a real-world HR automation task by parsing resumes and converting unstructured text into structured data for recruitment workflows.

## Approach:
Uses Hugging Face’s bert-base-NER model for accurate Named Entity Recognition (NER).

Extracted entities are mapped to categories like:

- Name

- Degree

- Institution

- Skills

- Work Experience

Skills can be further enhanced using predefined skill lists or keyword-matching techniques.

## Technologies Used:

- Python (in Google Colab)

- Hugging Face Transformers for the BERT NER model

- pdfminer.six to extract text from PDF resumes

- Regular expressions (re) for pattern matching (e.g., emails, phone numbers)


## Workflow:

- Upload .txt or .pdf resume file.

- Extract raw text using appropriate methods (pdfminer for PDFs).

- Run BERT-based NER on the text using Hugging Face pipelines.

- Filter and categorize entities into structured fields.

- Display the extracted information.


## Possible Enhancements:

- Enable batch processing for multiple resumes.

- Build a web interface using tools like Streamlit or Gradio for end-user interaction.
