# NLP PDF Processing Project

## Project Overview
This project performs complete Natural Language Processing (NLP) on a real PDF document (*The Time Machine*). It includes text extraction, preprocessing, feature extraction, and visualization using TF-IDF and Plotly.


## Features
- PDF text extraction using PyPDF2
- Regex-based text preprocessing (lowercase, remove numbers, symbols, extra spaces)
- Tokenization
- Stop word removal
- Stemming (Porter Stemmer)
- Lemmatization (WordNet Lemmatizer)
- One Hot Encoding
- TF-IDF feature extraction
- Data visualization using Plotly



## Visualizations
- Word Frequency Bar Chart
- TF-IDF Scatter Plot
- TF-IDF Heatmap



## Requirements
Install dependencies before running:

pip install PyPDF2 nltk pandas scikit-learn plotly



## How to Run

1. Clone the repository:

git clone https://github.com/your-username/nlp-project.git

2. Go to project folder:

cd nlp-project

3. Open notebook:

task.ipynb

4. Run all cells step by step.



## Dataset
The project uses:
The Time Machine (PDF Book)
Source: Project Gutenberg


## Outputs Included
- PDF loading output
- Total pages count
- Extracted text sample
- Regex preprocessing output
- Stop word count
- Valid word count
- Stemming output
- Lemmatization output
- One Hot Encoding output
- TF-IDF output
- Plotly graphs






## Author
Menahil Ikram



## Note
This project demonstrates a full NLP pipeline on real world text data using Python.
