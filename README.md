# PDF-Text-and-Table-Extraction-with-CSI-3-Part-Specification-Categorization

This repository contains a script to extract text and tabular data from a PDF file and categorize the text into submittal and product requirements using a language model. The script utilizes PyPDF2 for text extraction, tabula for table extraction, and cohere for natural language processing.

## Script Overview
The script performs the following steps:

**PDF Text and Table Extraction:**

- It reads a PDF file and extracts text from each page.
- It also extracts tables from each page using Tabula.

**Text Categorization:**

The extracted text is sent to the Cohere API to categorize the content into submittal and product requirements based on a predefined example.

**Data Organization:**

The categorized data is organized into a Pandas DataFrame for easy viewing and further analysis.

## Notes

- Ensure the PDF file path is correctly specified.
- Replace your_api_key_here with your actual Cohere API key.
- The script assumes that the PDF contains text and tables formatted in a way that is compatible with the extraction methods used.

## Example Output

- The script will print the extracted text and tables, followed by a DataFrame categorizing the requirements into submittal and product requirements.

## Usage

This README provides an overview of the script's functionality and how to use it. For more details, refer to the code comments and adjust the script as needed for your specific use case.
