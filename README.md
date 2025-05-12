# Text Generation and TF-IDF Analysis

This project implements a text generation and TF-IDF (Term Frequency-Inverse Document Frequency) analysis system using various Natural Language Processing (NLP) techniques. It combines text generation capabilities with advanced text processing and analysis features.

## Features

- **Text Generation**: Uses GPT-2 model for generating text based on given prompts
- **Text Preprocessing Pipeline**:
  - Text Cleaning (removes special characters)
  - Text Normalization (converts to lowercase)
  - Tokenization (splits text into words)
  - Lemmatization (reduces words to their base form)
  - Stopword Removal
  - Unique Word Extraction
- **TF-IDF Analysis**: Calculates and analyzes term frequencies in the generated text

## Requirements

- Python 3.x
- Required Python packages:
  - scikit-learn
  - nltk
  - transformers
  - numpy
  - pandas

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Yossefmohammed/Generate-docs-and-calc-TF-IDF.git
cd Generate-docs-and-calc-TF-IDF
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Download required NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

## Usage

The project is implemented as a Jupyter notebook (`Generate docs and calc TF-IDF.ipynb`). You can run it using Jupyter Notebook or Jupyter Lab.

The notebook demonstrates:
1. Text generation from prompts
2. Text preprocessing pipeline
3. TF-IDF analysis of the generated text

## Project Structure

- `Generate docs and calc TF-IDF.ipynb`: Main notebook containing the implementation
- `README.md`: Project documentation
- `requirements.txt`: List of required Python packages

## Features in Detail

### Text Generation
- Uses the GPT-2 model from Hugging Face's transformers library
- Generates text based on user-provided prompts
- Configurable maximum length for generated text

### Text Preprocessing
- **Cleaning**: Removes special characters and non-alphabetic content
- **Normalization**: Converts text to lowercase
- **Tokenization**: Splits text into individual words
- **Lemmatization**: Reduces words to their base form using WordNet
- **Stopword Removal**: Removes common English stopwords
- **Unique Word Extraction**: Identifies unique words in the processed text

### TF-IDF Analysis
- Calculates term frequencies
- Identifies important terms in the generated text
- Provides insights into the most significant words in the corpus

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.

## Author

Youssef Mohammed

### Contact Information
- Email: ypssefmohammedahmed@gmail.com
- Phone: 01126078938
