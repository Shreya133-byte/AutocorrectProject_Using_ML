# AI Autocorrect Tool

## Overview

The AI Autocorrect Tool is a Natural Language Processing (NLP) project developed using Python and TextBlob. The application automatically detects and corrects spelling mistakes in user-provided text.

This project demonstrates how NLP techniques can be used to improve text quality and assist users in writing error-free content.

## Features

* Corrects spelling mistakes automatically
* Accepts user input dynamically
* Displays original and corrected text
* Counts corrected words
* Supports multiple text correction attempts
* Saves correction history to a text file
* Easy-to-use command-line interface

## Technologies Used

* Python
* TextBlob
* NLTK


## Project Structure

Autocorrect_Tool/

├── autocorrect.ipynb

├── corrections.txt

├── README.md

└── requirements.txt


## Installation

Install the required libraries:

pip install textblob

python -m textblob.download_corpora


## Usage

Run the Jupyter Notebook and execute all cells.

Enter a sentence containing spelling mistakes.

Example:

Input:

I hav a dreem to becme an enginer

Output:

I have a dream to become an engineer


## Sample Output

Original Text:

Machne learnng is awsome

Corrected Text:

Machine learning is awesome


## Limitations

* TextBlob mainly performs spelling correction.
* It may not fully understand sentence context.
* Some grammatically incorrect sentences may not be corrected accurately.
* Advanced NLP models such as BERT can provide better contextual corrections.

---

## Future Enhancements

* Grammar correction using BERT
* GUI using Tkinter or Streamlit
* Voice-based text correction
* Multi-language support

---

## Conclusion

This project successfully demonstrates the implementation of an AI-based autocorrect system using Natural Language Processing techniques. The tool improves text quality by identifying and correcting spelling mistakes and serves as a foundation for more advanced NLP applications.
