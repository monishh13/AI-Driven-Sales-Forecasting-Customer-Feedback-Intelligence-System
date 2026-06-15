# AI-Driven Sales Forecasting & Customer Feedback Intelligence System

## Overview

This project integrates **Time Series Forecasting**, **Natural Language Processing (NLP)**, and **Generative AI** to help retail businesses predict future sales while understanding customer sentiment and demand drivers.

The system automates the entire workflow from data preprocessing to executive-level insight generation.

---

## Problem Statement

Retail organizations often face challenges such as:

- Inaccurate sales forecasting due to seasonality
- Underutilized customer feedback
- Manual and time-consuming analysis
- Lack of automated business insights

This project addresses these challenges using Machine Learning and AI.

---

## Features

### Time Series Forecasting

- ARIMA
- SARIMA
- SARIMAX
- Model performance comparison
- Future sales prediction

### NLP Pipeline

- Text preprocessing
- Sentiment Analysis using VADER
- Customer feedback classification
- Keyword extraction

### fastText Integration

- Generates fastText-compatible training data
- Ready for advanced text classification

### GenAI Insight Generation

- Automated executive summary
- Business recommendations
- Forecast interpretation
- Customer sentiment analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- NLTK
- Jupyter Notebook

---

## Dataset

### Sales Dataset

| Column |
|----------|
| date |
| sales |
| promo |
| holiday |
| weather_index |

### Customer Reviews Dataset

| Column |
|----------|
| review_id |
| review_comment |
| true_sentiment |

---

## Workflow

```
Sales Data
      |
      V
Data Cleaning
      |
      V
ARIMA / SARIMA / SARIMAX
      |
      V
Sales Forecast

Customer Reviews
      |
      V
Text Preprocessing
      |
      V
VADER Sentiment Analysis
      |
      V
Text Classification
      |
      V
fastText Dataset

Forecast + NLP Results
          |
          V
GenAI Narrative Report
          |
          V
Business Decision Support
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Driven-Sales-Forecasting-Customer-Feedback-Intelligence-System.git

cd AI-Driven-Sales-Forecasting-Customer-Feedback-Intelligence-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
AI_Driven_Sales_Forecasting_Customer_Feedback_Intelligence_System.ipynb
```

---

## Output

The project generates:

- Sales Forecast
- Customer Sentiment Report
- Model Performance Metrics
- Executive Narrative Report
- fastText Training Dataset

---

## Future Enhancements

- Prophet Forecasting
- XGBoost Forecasting
- BERT Sentiment Analysis
- BERTopic Topic Modeling
- OpenAI API Integration
- Streamlit Dashboard
- MLflow Deployment

---

## Project Architecture

```
                 +------------------+
                 |   Sales Data     |
                 +------------------+
                           |
                           V
               +--------------------+
               | ARIMA/SARIMA/X     |
               +--------------------+
                           |
                           V
                  Sales Forecast

                 +------------------+
                 | Customer Reviews |
                 +------------------+
                           |
                           V
                 NLP Preprocessing
                           |
                           V
                Sentiment Analysis
                           |
                           V
                Text Classification
                           |
                           V
                  fastText Dataset

          +--------------------------------+
          | Forecast + NLP + GenAI Report |
          +--------------------------------+
                           |
                           V
                 Business Intelligence
```


## License

This project is licensed under the MIT License.
