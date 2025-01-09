# Sentence-Level Tokenizer
**About the Project**
This model tokenizes text into sentences using NLTK’s sentence tokenizer and a custom regex-based method for efficient sentence segmentation.

# Project Implementation and Workflow**
**NLTK Sentence Tokenization:**
Uses NLTK’s pre-trained sent_tokenize function to detect sentence boundaries.
**Regex-Based Tokenization:**
Implements custom regex patterns to split text into sentences based on punctuation and whitespace.
**Comparison and Output:**
Saves the tokenized sentences from both methods into a CSV file for analysis and comparison.
# Required Packages to Import
**Pandas:** To handle the dataset and save results.
**NLTK:** For pre-trained sentence tokenization.
**Re (Regex):** For custom sentence segmentation.

**Install dependencies using:**
```bash
pip install pandas nltk
python -m nltk.downloader punkt
```
