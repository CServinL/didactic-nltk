# Didactic NLTK

A didactic repository to demonstrate how to use the NLTK (Natural Language Toolkit) Python module.

## Overview

This repository provides examples and tutorials for working with NLTK, a leading platform for building Python programs to work with human language data. You can follow along using either Jupyter notebooks or plain Python scripts.

## Prerequisites

- Python 3.13 or higher
- [Poetry](https://python-poetry.org/) (Python dependency management tool)

## Installation

### Install Poetry

If you don't have Poetry installed, follow the [official installation guide](https://python-poetry.org/docs/#installation) or use:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

### Set Up the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/CServinL/didactic-nltk.git
   cd didactic-nltk
   ```

2. Install dependencies using Poetry:
   ```bash
   poetry install
   ```

3. Activate the virtual environment:
   ```bash
   poetry shell
   ```

## Getting Started

### Option 1: Using Jupyter Notebooks

1. Start Jupyter Notebook:
   ```bash
   poetry run jupyter notebook
   ```

2. Navigate to the notebook files in your browser and start exploring!

### Option 2: Using Plain Python Scripts

1. Run any Python script using Poetry:
   ```bash
   poetry run python script_name.py
   ```

   Or activate the shell first:
   ```bash
   poetry shell
   python script_name.py
   ```

## NLTK Data

NLTK requires additional data packages for most operations. Download them using:

```python
import nltk
nltk.download('popular')  # Downloads popular datasets
```

Or download specific packages:

```python
nltk.download('punkt')      # Tokenizer
nltk.download('stopwords')  # Stop words
nltk.download('wordnet')    # WordNet lexical database
nltk.download('averaged_perceptron_tagger')  # POS tagger
```

## Topics Covered

This repository demonstrates various NLTK functionalities including:

- **Tokenization**: Breaking text into words and sentences
- **Part-of-Speech Tagging**: Identifying grammatical roles
- **Stop Words**: Filtering common words
- **Stemming and Lemmatization**: Word normalization
- **Named Entity Recognition**: Identifying entities in text
- **Text Classification**: Categorizing text documents
- **Sentiment Analysis**: Determining emotional tone

## Repository Structure

```
didactic-nltk/
├── notebooks/          # Jupyter notebooks with examples
├── scripts/           # Plain Python scripts
├── data/              # Sample data files
└── README.md          # This file
```

## Contributing

Feel free to contribute by adding more examples or improving existing ones!

## Resources

- [NLTK Official Documentation](https://www.nltk.org/)
- [NLTK Book](https://www.nltk.org/book/)
- [Python Official Documentation](https://docs.python.org/3/)

## License

See the [LICENSE](LICENSE) file for details.
