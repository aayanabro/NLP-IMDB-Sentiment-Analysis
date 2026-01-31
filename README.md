# IMDB Movie Reviews Text Classification

This project implements a Natural Language Processing (NLP) pipeline to classify IMDB movie reviews as either **Positive** or **Negative**. The project covers data cleaning, text preprocessing, and sentiment analysis using Python.

## 📊 Dataset
The dataset used in this project is the **IMDB Dataset**, which contains 50,000 movie reviews. For computational efficiency in this notebook, a subset of the first 10,000 reviews was used.

- **Total Rows (Subsampled):** 10,000
- **Columns:** `review` (Text), `sentiment` (Label: positive/negative)

## 🛠️ Tech Stack
- **Python**
- **Pandas & NumPy** (Data manipulation)
- **NLTK** (Natural Language Toolkit)
- **Regex (re)** (Text cleaning)

## 🧹 Data Preprocessing
The following preprocessing steps were performed to prepare the text for classification:
1. **Handling Duplicates:** Identified and removed duplicate reviews to ensure data integrity.
2. **HTML Tag Removal:** Used regular expressions to strip HTML tags (e.g., `<br />`) from the raw review text.
3. **Lowercasing:** Converted all text to lowercase for uniformity.
4. **Stopword Removal:** Removed common English stopwords (e.g., "the", "is", "in") using the NLTK library to focus on meaningful words.

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Pandas
- NumPy
- NLTK
