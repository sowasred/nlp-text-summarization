# NLTK Text Summarization

This Python script uses the NLTK library to summarize text input by the user. The script tokenizes the input text into words and sentences, calculates word frequencies, and scores sentences based on word frequency. It then selects the top seven sentences with the highest scores to create a summary of the original text.

## Prerequisites

- Install Python 3.x
- Install NLTK library: `pip install nltk`
- Download the necessary NLTK data (stopwords) by running the following command in your Python environment:

```python
import nltk
nltk.download('stopwords')
```

## Usage

1. Run the script using a Python interpreter or IDE.
2. Enter the text you want to summarize when prompted.
3. The script will display the summary of the input text based on the extracted sentences with the highest word frequency scores.
