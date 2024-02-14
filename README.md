# spaCy NLP Example
This repository contains a Python script that demonstrates the use of spaCy, a powerful and efficient library for natural language processing (NLP) in Python. The script showcases several key features of spaCy, including tokenization, part-of-speech (POS) tagging, named entity recognition (NER), and dependency parsing.

## Overview
The Python script (spacy_example.py) processes a sample text to illustrate how spaCy can be used for various NLP tasks. The example text used is: "Apple is looking at buying U.K. startup for $1 billion".

## Features Demonstrated
- <b>Tokenization</b>: Splitting the text into individual words and punctuation.
- <b>Lemma</b>: The base form of the words.
- <b>Part-of-Speech Tagging</b>: Assigning word types to tokens, such as verb, noun, and adjective.
- <b>Dependency Parsing</b>: Analyzing the grammatical structure of a sentence, establishing relationships between "head" words and words which modify those heads.
- <b>Named Entity Recognition</b>: Identifying and classifying key information (entities) in the text into predefined categories such as the names of organizations, places, monetary values, etc.
- <b>Additional Token Attributes</b>: Demonstrating token attributes like shape, is_alpha, and is_stop to understand the characteristics of each token.

## Requirements
To run this script, you will need:

- Python 3.6+
- spaCy library
- English language model for spaCy (en_core_web_sm)

## Setup and Execution
1. Ensure you have Python installed on your system.

2. Install spaCy using pip:

```
pip install spacy
```

3. Download the English language model:

```
python -m spacy download en_core_web_sm
```

4. Clone this repository and navigate into the project directory.

## Output
The script will output:

A list of tokens along with their lemma, POS tag, detailed tag, dependency relation, shape, and boolean flags for alphabetical characters and stopwords.
The named entities recognized in the text, along with their type.

## Contributing
Contributions are welcome! If you have suggestions for improving this example, feel free to open an issue or submit a pull request.

## License
This project is open-source and available under the MIT License.
