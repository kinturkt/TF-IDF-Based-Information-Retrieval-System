# **TF-IDF Based Information Retrieval System**

## **Project Overview**
This project implements a text-processing pipeline for retrieving and analyzing U.S. Presidential Inaugural Addresses using **TF-IDF (Term Frequency-Inverse Document Frequency)** and **Cosine Similarity**. The system processes text data to enable efficient document retrieval based on user queries.

## **Features**
- **Preprocessing:** Converts text to lowercase, tokenizes, removes stopwords, and applies stemming.
- **TF-IDF Calculation:** Computes term frequency and inverse document frequency values for each word in the corpus.
- **Document Retrieval:** Uses **Cosine Similarity** to find the most relevant document for a given query.
- **Efficient Query Processing:** Returns the document with the highest similarity score for a given search phrase.

## **Technologies Used**
- Python
- Pandas
- NumPy
- NLTK (Natural Language Toolkit)
- Collections & Math Libraries

## **Dataset**
The dataset consists of **U.S. Presidential Inaugural Addresses**, stored as `.txt` files in the `US_Inaugural_Addresses` directory.

## **Installation & Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. Install dependencies:
   ```bash
   pip install pandas numpy nltk

3. Download NLTK stopwords:
   ```bash
   import nltk
   nltk.download('stopwords')

4. Run the Python script:
   python main.py

## Project Structure
```bash

├── US_Inaugural_Addresses/  # Folder containing text documents
├── main.py                  # Main script for processing and retrieval
├── README.md                # Project documentation
├── requirements.txt         # Required dependencies

## Author: Kintur Shah
[LinkedIn](https://www.linkedin.com/in/kintur-shah/) | [Github](https://github.com/kinturkt)
