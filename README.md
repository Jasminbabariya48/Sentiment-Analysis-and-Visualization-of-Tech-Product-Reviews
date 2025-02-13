# Amazon Review Sentiment Analysis & Summarization

## Overview
This project performs **sentiment analysis and summarization** on Amazon product reviews using NLP techniques. It leverages web scraping, deep learning models, and visualization tools to extract insights from customer feedback.

## Features
- **Web Scraping**: Extracted reviews using `BeautifulSoup`.
- **Sentiment Analysis**: Applied multiple ML models to classify reviews.
- **Summarization**: Generated concise summaries of reviews.
- **Data Visualization**: Insights displayed using Power BI.

## Dataset
- **Source**: Amazon product pages.
- **Size**: 3,867 reviews.
- **Columns**:
  - Product details: `category`, `brand`, `model`.
  - Review details: `review_text`, `review_stars`.
  - Sentiment analysis: Results from 5 models and majority voting.

## Methodology
1. **Data Preprocessing**
   - Cleaned text data (removing HTML tags, special characters, etc.).
   - Tokenization and lemmatization.
2. **Sentiment Classification**
   - Used multiple models (`Hugging Face transformers`).
   - Assigned sentiment labels: Positive, Neutral, Negative.
3. **Review Summarization**
   - Generated concise summaries using `LLMs`.
4. **Data Visualization**
   - Created sentiment distribution plots.
   - Power BI dashboard for interactive insights.

## Tech Stack
- **Languages**: Python
- **Libraries**: BeautifulSoup, Pandas, NLTK, Transformers, Matplotlib, Seaborn
- **Tools**: Jupyter Notebook, Power BI

## Results
- Achieved **high accuracy in sentiment classification** using ensemble voting.
- Created **meaningful visualizations** for business insights.
- Summarized customer reviews effectively for better understanding.

## How to Run
1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook Amazon_Review_Sentiment_and_Summarization.ipynb
   ```
3. Open Power BI to explore the interactive dashboard.

## Repository Structure
```
|-- data/
|   |-- sentiment_analysis.csv  # Processed dataset
|-- notebooks/
|   |-- Amazon_Review_Sentiment_and_Summarization.ipynb
|-- visualizations/
|   |-- powerbi_dashboard.pbix
|-- README.md
|-- requirements.txt
```

## Future Improvements
- Extend to more product categories.
- Improve sentiment classification with fine-tuned models.
- Automate data pipeline for real-time analysis.

## Contributors
- **[Your Name]**

