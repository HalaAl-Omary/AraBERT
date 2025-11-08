# AraBERT Arabic NLP Project

## Overview

This project utilizes **AraBERT**, a pre-trained transformer-based model for Arabic language understanding, to perform **natural language processing (NLP) tasks** such as text classification, sentiment analysis, and question answering. The project demonstrates how to preprocess Arabic text, fine-tune the AraBERT model, and use it for predictions.

## Features

* Preprocessing of Arabic text: normalization, tokenization, and cleaning
* Fine-tuning AraBERT for specific NLP tasks
* Easy integration with Python scripts for inference
* Example datasets for testing and training

## Requirements

* Python 3.8+
* [Transformers](https://huggingface.co/transformers/)
* [PyTorch](https://pytorch.org/)
* [Pandas](https://pandas.pydata.org/)
* [Scikit-learn](https://scikit-learn.org/)
* [AraBERT Model](https://huggingface.co/aubmindlab/bert-base-arabertv2)

Install dependencies using:

```bash
pip install transformers torch pandas scikit-learn
```

## Project Structure

```text
AraBERT_Project/
│
├── data/               # Training and testing datasets
├── models/             # Saved fine-tuned models
├── scripts/            # Python scripts for preprocessing, training, and inference
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies
```

## References

* [AraBERT on Hugging Face](https://huggingface.co/aubmindlab/bert-base-arabertv2)
* [Hugging Face Transformers Documentation](https://huggingface.co/transformers/)

## License

This project is licensed under the MIT License.
