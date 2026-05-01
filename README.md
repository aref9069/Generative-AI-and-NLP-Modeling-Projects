# Generative AI and NLP Modeling Projects

This repository contains a collection of hands-on Generative AI and Natural Language Processing projects focused on text preprocessing, tokenization, language modeling, word embeddings, document classification, and sequence-to-sequence modeling. The work demonstrates end-to-end NLP workflows using Python, PyTorch, TorchText, Hugging Face Transformers, spaCy, NLTK, and Gensim.

## Project Overview

The goal of this project is to build a strong foundation in Generative AI and NLP by implementing core components of modern language systems, from text preprocessing and data loading to neural language models and document classification.

The repository includes multiple notebook-based modules covering:

- Text preprocessing, tokenization, vocabulary creation, and frequency analysis
- NLP data loading pipelines using PyTorch, TorchText, and custom datasets
- Histogram-based N-gram language modeling
- Feedforward neural network language modeling
- Word2Vec, CBOW, Skip-Gram, and embedding visualization
- Document classification using AG_NEWS and PyTorch
- Sequence-to-sequence RNN modeling for machine translation
- Exploration of pretrained Generative AI models using Hugging Face Transformers

## Repository Structure

```text
.
├── GenAI- Implementing Tokenization.ipynb
├── GenAI- Creating an NLP Data Loader.ipynb
├── GenAI- Building a Language Model Using Histogram N-Gram Analysis.ipynb
├── GenAI- Building and Training a Feedforward Neural Network for Language Modeling.ipynb
├── GenAI- Integrating Word2Vec for Language Modeling_ Part1.ipynb
├── GenAI- Integrating Word2Vec for Language Modeling_ Part2.ipynb
├── GenAI- Classifying Documents.ipynb
├── GenAI- Developing a Sequence-to-Sequence RNN Model for Language Modeling.ipynb
└── GenAI- Exploring Generative AI Libraries.ipynb
```

## Key Features

- Built NLP preprocessing pipelines for cleaning, tokenizing, and numericalizing text data.
- Implemented custom PyTorch `Dataset`, `DataLoader`, and `collate_fn` workflows.
- Developed classical and neural language models using N-grams and feedforward neural networks.
- Integrated Word2Vec, CBOW, Skip-Gram, and GloVe-style embeddings for semantic representation learning.
- Trained text classification models on the AG_NEWS dataset using PyTorch and TorchText.
- Built encoder-decoder sequence-to-sequence RNN models for translation-style language modeling.
- Explored pretrained transformer-based models using Hugging Face Transformers.

## Technologies Used

- Python
- PyTorch
- TorchText
- TorchData
- Hugging Face Transformers
- spaCy
- NLTK
- Gensim
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly

## Main Learning Outcomes

Through this project, I developed practical experience in building NLP and Generative AI pipelines from the ground up. The work covers the full workflow of preparing text data, creating vocabularies and embeddings, designing neural network architectures, training models, evaluating performance, and applying pretrained generative models.

## Example Applications

- Text classification
- Language modeling
- Word embedding analysis
- Semantic similarity search
- Machine translation
- Chatbot experimentation
- Generative AI model exploration

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

2. Install the main dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn nltk spacy gensim transformers sentencepiece torch torchtext torchdata
```

3. Download spaCy language models:

```bash
python -m spacy download en_core_web_sm
python -m spacy download de_core_news_sm
```

4. Open the notebooks:

```bash
jupyter notebook
```

## Project Summary

This repository demonstrates a progressive learning path in Generative AI and NLP, starting from tokenization and text representation and advancing toward neural language modeling, document classification, embeddings, and sequence-to-sequence generation. It highlights practical implementation skills in PyTorch-based NLP modeling and the use of modern Generative AI libraries.

