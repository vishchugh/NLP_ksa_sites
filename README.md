# 📌 NLP Analysis of Google Reviews for Saudi Arabian Sites

## 📝 Project Overview
Online reviews provide valuable customer feedback, offering insights into service quality, popularity, and areas needing improvement. This project focuses on analyzing Google reviews for multiple sites in Saudi Arabia using Natural Language Processing (NLP). The goal is to extract meaningful insights from unstructured review text and JSON-encoded data.

## 🎯 Objectives
1. **Data Transformation & Preprocessing**
   - Extract structured information from JSON-encoded columns (tags, ratings).
   - Map hashkeys in the `tags` column to offerings (e.g., accommodation, tourist attractions) and destinations (e.g., Riyadh, Jeddah).
   - Generate new columns for user ratings and perform sentiment classification (positive, neutral, negative).

2. **Text Cleaning & NLP Analysis**
   - Preprocess review text (removing stop words, stemming, tokenization, etc.).
   - Identify common themes, keywords, and categories from customer feedback.
   
3. **Exploratory Data Analysis (EDA)**
   - Analyze the distribution of sentiments, offerings, destinations, and ratings.
   - Identify patterns and correlations between variables (e.g., sentiment vs. ratings).

## 📂 Dataset
- **Google Reviews Dataset (CSV, 10k rows)**: Contains reviews for multiple sites in Saudi Arabia.
- **Mapping File (JSON)**: Provides mappings for hashkeys in the `tags` column to specific offerings and destinations.

## 📌 Deliverables
1. **Jupyter Notebook**
   - Well-documented and modular code for data preprocessing, sentiment analysis, NLP, and EDA.
   - Visualizations to illustrate key findings.

2. **PDF Report**
   - **Methodology**: Detailed explanation of sentiment analysis, text cleaning, and data transformation techniques.
   - **Findings**: Insights from sentiment analysis, keyword extraction, and EDA.
   - **Recommendations**: Strategic suggestions for businesses based on customer feedback.

## 🚀 Installation & Setup
1. Clone the repository:
   ```bash
   https://github.com/vishchugh/NLP_ksa_sites.git
   cd NLP_ksa_sites
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage
Run the Jupyter Notebook to execute data preprocessing, sentiment analysis, and EDA:
```bash
jupyter notebook
```

## 📊 Evaluation Criteria
- **Data Transformation Accuracy**: Correct mappings and structured transformations.
- **Sentiment Analysis Effectiveness**: Accuracy of sentiment classification.
- **Text Cleaning & NLP Quality**: Appropriateness of preprocessing techniques.
- **EDA Insights**: Depth and relevance of insights from analysis.
- **Clarity of Deliverables**: Well-structured report and documentation.

## 📄 License
This project is licensed under the MIT License.

---

