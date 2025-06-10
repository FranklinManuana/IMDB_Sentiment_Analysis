# Load dataset

## Overview

This project performs sentiment analysis on IMDB movie reviews using a BERT-based deep learning model.
It compares the performance of pre-trained and untrained transformer models, traditional ML baselines, and evaluates performance with various metrics.

Load dataset
Classic Machine Learning
LLM Models

## Features

- Preprocessing of text data (HTML tag and punctuation removal, tokenization)
- Dataset loading using Hugging Face's `datasets` library
- Fine-tuning a DistilBERT model
- Evaluation with accuracy, confusion matrix, and classification report
- Comparison with untrained transformer model

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-bert.git
   cd sentiment-analysis-bert
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `sentiment_Final.ipynb` in Jupyter Notebook or Google Colab.

## Dataset

- IMDB dataset from the Hugging Face `datasets` library:
  ```python
  from datasets import load_dataset
  ds = load_dataset("imdb")
  ```

## Results

The project compares:
- A pre-trained DistilBERT model
- An untrained DistilBERT model
- Optional: traditional machine learning baselines (e.g., Logistic Regression)

## Example Output

- Accuracy: ~X.XX
- Confusion Matrix and Classification Report displayed in output cells

## Contributing

Feel free to fork this repository, make changes, and create a pull request.

## License

[MIT License](LICENSE)

## Contact

For questions or collaboration, reach out to: your_email@example.com
