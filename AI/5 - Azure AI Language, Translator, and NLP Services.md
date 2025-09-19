# Chapter 5: Azure AI Language, Translator, and NLP Services

## Introduction to Natural Language Processing (NLP)

NLP is a branch of AI focused on enabling machines to understand, interpret, and generate human language. It leverages advanced models like transformers to perform tasks such as sentiment analysis, entity recognition, and translation.

---

## Core NLP Concepts

### Corpus

- A large, structured collection of text documents used for training and analysis.
- Plural form: corpora.

### Tokenization

- The process of breaking text into meaningful units called tokens.
- Helps models analyze text by converting it into manageable pieces.

#### Tokenization Techniques

1. **Text Normalization:** Lowercasing text and removing punctuation.
2. **Stop Word Removal:** Excluding common, less meaningful words like "the" and "and".
3. **n-grams:** Grouping tokens into sequences (unigrams, bigrams, trigrams).
4. **Stemming:** Reducing words to their root form (e.g., "powered" to "power").

### Statistical NLP Techniques

- **Naive Bayes:** Used for classification, like spam detection, based on word frequency.
- **TF-IDF (Term Frequency-Inverse Document Frequency):** Weighs how important a word is in a document relative to the corpus.

---

## Azure AI Language Service

A cloud-based service providing advanced NLP capabilities on unstructured text.

### Key Features

- **Named Entity Recognition (NER):** Identifies names of people, places, organizations, and more.
- **Entity Linking:** Links recognized entities to external knowledge bases like Wikipedia.
- **Personally Identifiable Information (PII) Detection:** Identifies sensitive personal data.
- **Language Detection:** Detects the language of the text with language codes (e.g., "en" for English).
- **Sentiment Analysis:** Detects positive, negative, or neutral tone in text.
- **Text Summarization:** Produces concise summaries of longer texts.
- **Key Phrase Extraction:** Identifies main concepts or important phrases.

---

## Azure AI Language Conversational Features

- **Question Answering:** Build chatbots that respond to customer queries.
- **Conversational Language Understanding (CLU):** Detects user intent and extracts information for command-and-control scenarios, multi-turn dialogues, and enterprise support.

---

## Azure AI Translator Service

Provides Neural Machine Translation (NMT) for accurate, real-time language translation.

### Capabilities

- **Text Translation:** Fast, context-aware translation of text.
- **Document Translation:** Translate multiple documents preserving formatting and structure.
- **Custom Translation:** Build tailored translation models using proprietary datasets.

---
