# BBC News Machine Learning Research

## Project Overview

This repository contains the dataset and code used for machine learning research on BBC news articles.

The project investigates news text characteristics including classification, text complexity, readability, summarization, and potential machine learning research directions.

## Dataset

The complete dataset is available in this repository:

`bbc_news_text_complexity_summarization.csv`

The dataset contains BBC news articles together with information related to news categories, text complexity, readability, and extractive summaries.

### Main Dataset Features

- Original news article text
- News category labels
- Number of sentences
- Flesch Reading Ease Score
- Dale-Chall Readability Score
- TextRank-generated summary
- LSA-generated summary

The news articles belong to five categories:

- Business
- Entertainment
- Politics
- Sport
- Tech

## Code

The current analysis code is provided as a Jupyter Notebook:

`ML_Tool (1).ipynb`

The notebook was used for systematic dataset inspection and machine learning research preparation.

The analysis workflow includes:

- Dataset loading and validation
- Dataset structure analysis
- Data quality assessment
- Column-level analysis
- Missing-value and duplicate analysis
- Numerical and categorical statistics
- Distribution analysis
- Correlation analysis
- Outlier analysis
- Class-balance analysis
- Target and feature assessment
- Data leakage and usability checks
- Machine learning readiness assessment
- Feature-engineering recommendations
- Research problem identification
- Preparation for subsequent machine learning stages

## Research Direction

The broader research investigates how machine learning and natural language processing methods can be applied to BBC news data for tasks such as:

1. News category classification
2. Readability and text-complexity prediction
3. Summary-based document classification
4. Multi-view learning using original text, TextRank summaries, and LSA summaries
5. Semi-supervised learning
6. Explainable machine learning

## Repository Contents

- `bbc_news_text_complexity_summarization.csv` — Complete research dataset
- `ML_Tool (1).ipynb` — Dataset analysis and ML research preparation code
- `README.md` — Project documentation

## Project Status

The repository is being maintained as part of an ongoing machine learning research project. Additional preprocessing, modeling, evaluation, and experimental code will be added as the research progresses.
