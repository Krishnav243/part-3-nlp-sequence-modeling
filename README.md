# Part 3: NLP and Sequence Modeling Mini Project

## Project Overview

This project focuses on Natural Language Processing (NLP) and sequence modeling using customer support text data.

The objective is to understand:

- Text preprocessing
- Text vectorization
- Baseline NLP modeling
- Sequence modeling using LSTM
- Attention and transformer concepts

The goal is to classify customer support messages into sentiment categories.

---

## Dataset Understanding

### Dataset Information

- **Number of records:** 1500
- **Number of columns:** 6

### Target Labels / Classes

The dataset contains three sentiment classes:

- Positive
- Neutral
- Negative

### Class Distribution

- Neutral: 524
- Negative: 497
- Positive: 479

The dataset is balanced because all classes contain similar numbers of records.

### Sample Text Records

Customer support messages were analyzed to understand text patterns and sentiment labels.

### Average Text Length

Average text length:

**72.76 characters**

---

## Text Preprocessing

The following preprocessing steps were applied:

- Lowercasing
- Removing special characters and symbols
- Tokenization
- Stopword removal

Example:

### Original Text
```text
I need information about the payment process. My ticket number is 78732.
