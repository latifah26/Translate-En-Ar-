# Translate-En-Ar
English-to-Arabic Translation This project focuses on machine translation from English to Arabic using deep learning techniques. The goal is to build a model that can automatically translate sentences written in English into their correct Arabic equivalents.

The main steps in the project are:

Data Preprocessing: The dataset consists of sentence pairs (English ↔ Arabic) loaded from a text file. Sentences are tokenized, padded, and converted into numerical sequences using custom vocabularies.

Vocabulary Creation: Word-to-index dictionaries (vocabularies) are created separately for English and Arabic. Special tokens like <pad>, <sos>, <eos>, and <unk> are added to handle padding, sentence boundaries, and unknown words.

Data Splitting: The dataset is divided into training, validation, and test sets to evaluate model performance at different stages.

Model Training: Using PyTorch, an encoder-decoder architecture (e.g., RNN, LSTM, or Transformer) can be trained to learn the mapping from English input sequences to Arabic output sequences.

This translation task is useful for a variety of real-world applications such as:

Cross-lingual communication

Arabic language learning tools

Assisting in medical, legal, or governmental translation tasks
