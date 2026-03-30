# NLP-Autocorrection-System
A context-aware spell checking system built using Natural Language Processing (NLP) techniques. This project corrects spelling mistakes in sentences by combining unigram probabilities, bigram context modeling, and edit distance using SymSpell. It also includes a simple and interactive GUI built with Gradio for real-time usage.

## 🚀 Overview

This project focuses on building an intelligent auto-correction system that not only fixes spelling errors but also considers the context of words within a sentence. Unlike basic spell checkers, it uses probabilistic models to choose the most appropriate correction based on surrounding words.

## ✨ Features
Context-aware sentence correction
Unigram-based word probability calculation
Bigram model for contextual understanding
Fast candidate generation using SymSpell
Handles unknown words and spelling errors efficiently
Preserves capitalization of words
Interactive GUI using Gradio
## 🧠 Working Principle

The system works in multiple stages:

Tokenization
The input sentence is broken into individual words.
Unigram Probability
Each word is assigned a probability based on its frequency in the corpus.
Bigram Probability
The probability of a word is adjusted based on the previous word to maintain context.
Candidate Generation
Possible corrections are generated using edit distance (insert, delete, replace, swap) via SymSpell.
Final Selection
The best correction is chosen using a combination of unigram and bigram probabilities.
## 📂 Dataset
NLTK Treebank Corpus
Used to build vocabulary and calculate word frequencies
🛠️ Tech Stack
Python
NLTK
SymSpell (symspellpy)
Gradio
## ▶️ Usage
Run the main script or notebook
Enter a sentence with spelling mistakes
Get corrected output instantly

If using GUI:

Launch Gradio interface
Enter text in input box
Click button to get corrected sentence
