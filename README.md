# News Sentiment Analysis

## Overview

This project focuses on exploratory data analysis (EDA) of financial news headlines to uncover trends, patterns, and insights that can support future sentiment analysis and financial forecasting tasks.

The analysis includes:

- Descriptive statistics
- Headline text analysis
- Topic modeling
- Time-series analysis
- Publisher analysis
- Visualization of publishing trends

---

# Project Structure

```text
news-sentiment-analysis/
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── data/
│   └── raw_analyst_ratings.csv
├── notebooks/
│   ├── __init__.py
│   └── task1_eda.ipynb
├── src/
│   ├── __init__.py
│   ├── preprocessing.py
│   ├── visualization.py
│   └── topic_modeling.py
├── tests/
│   ├── __init__.py
│   └── test_preprocessing.py
└── scripts/
    ├── __init__.py
    └── README.md
```

---

# Objectives

The main objectives of this project are:

- Understand the structure of the financial news dataset
- Analyze headline characteristics
- Identify dominant publishers
- Discover common keywords and topics
- Examine news publication trends over time
- Prepare the dataset for future sentiment analysis tasks

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- WordCloud
- Jupyter Notebook
- Git & GitHub
- GitHub Actions (CI/CD)

---

# Setup Instructions

## 1. Clone the Repository

```bash
git clone <your-repository-url>
cd news-sentiment-analysis
```

---

## 2. Create Virtual Environment

### Linux / macOS

```bash
python -m venv venv
source venv/bin/activate
```

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/task1_eda.ipynb
```

---

# Exploratory Data Analysis Tasks

## 1. Dataset Inspection

- Checked dataset structure
- Identified missing values
- Examined data types

---

## 2. Headline Length Analysis

- Calculated headline character counts
- Visualized distribution of headline lengths

### Insight

Most financial headlines are concise and focused on delivering quick market information.

---

## 3. Publisher Analysis

- Identified the most active publishers
- Compared article contribution frequency

### Insight

A small number of financial publishers contribute the majority of articles.

---

## 4. Time-Series Analysis

- Analyzed daily publication frequency
- Visualized changes in news volume over time

### Insight

Significant spikes in publication volume may correspond to important financial events or market activity.

---

## 5. Publishing Hour Analysis

- Extracted publication hours
- Examined hourly publishing patterns

### Insight

Most articles are published during active market and business hours.

---

## 6. Keyword Extraction (TF-IDF)

- Extracted important keywords from headlines
- Ranked keywords by TF-IDF score

### Insight

Frequent terms such as earnings, shares, market, and price target dominate financial news headlines.

---

## 7. Word Cloud Visualization

- Visualized frequently occurring words in headlines

### Insight

The word cloud highlights dominant themes and commonly discussed financial topics.

---

## 8. Topic Modeling (LDA)

- Applied Latent Dirichlet Allocation (LDA)
- Extracted hidden topics from headlines

### Example Topics

- Earnings reports
- Stock recommendations
- FDA approvals
- Mergers and acquisitions
- Market performance

---

## 9. Publisher Domain Analysis

- Extracted domains from publisher email addresses
- Identified organizational contribution patterns

### Insight

Major financial media organizations account for a large share of published articles.

---

# Visualizations Included

The notebook contains several visualizations, including:

- Headline length distribution
- Top publishers bar chart
- News publication trend over time
- Publishing frequency by hour
- Word cloud visualization

---

# CI/CD Configuration

GitHub Actions is configured for continuous integration.

The workflow automatically:

- Installs dependencies
- Runs tests using pytest

Workflow file:

```text
.github/workflows/unittests.yml
```

---

# Example Git Commit Messages

This project follows Conventional Commits:

```bash
feat: add exploratory data analysis notebook
feat: implement topic modeling analysis
chore: configure github actions workflow
docs: update project README
```

---

# Future Improvements

- Sentiment analysis using NLP models
- Stock price correlation analysis
- Named entity recognition (NER)
- Financial event detection
- Interactive dashboards

---

# Author

Name: Welela Bekele