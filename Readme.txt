
# Invoice NER with PaddleOCR and spaCy

This project extracts text from PDFs and images, performs Named Entity Recognition (NER) using a custom-trained spaCy model, and outputs results in JSON format.

## Features
- Extract text using PaddleOCR
- Named Entity Recognition (NER) using a custom-trained spaCy model
- Handle both PDFs and images

Code file has 2 codes and 1 Model file. 

1) NER_source code_testing
This code shows the extracted text before NER then process the text with the spaCy NER model and prints extracted entities and their labels in regular text. 

2) FVersion_JSON_NER
This performs NER using spaCy model and shows output directly in JSON format.
This zip contains the training data as well. We just need to replace the files location path to re-train using any code file as per wish. 

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/MTalhaa14/NER-for-Invoices/
cd NER-for-Invoices
pip install -r requirements.txt
