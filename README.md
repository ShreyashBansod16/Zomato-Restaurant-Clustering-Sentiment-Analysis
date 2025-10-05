# Zomato Restaurant Analysis & Sentiment Analysis Project

## Overview
This project analyzes Zomato restaurant data and customer reviews using machine learning and natural language processing techniques. The analysis includes restaurant metadata exploration, cuisine analysis, customer review sentiment analysis, and clustering of restaurants based on various features.

## Features

### 🍽️ Restaurant Data Analysis
- **Restaurant Metadata Analysis**: Explore restaurant names, costs, cuisines, and collections
- **Cost Analysis**: Identify most expensive and most affordable restaurants
- **Cuisine Analysis**: Analyze popular cuisine combinations and patterns
- **Missing Data Visualization**: Heatmap visualization of missing values

### 📊 Review Sentiment Analysis
- **Sentiment Polarity**: Analyze positive, negative, and neutral sentiments
- **Subjectivity Analysis**: Measure opinion vs. factual content in reviews
- **Rating Analysis**: Correlation between ratings and review characteristics
- **Top Reviewers**: Identify most active reviewers and their rating patterns

### 🔍 Natural Language Processing
- **Text Preprocessing**: Stopword removal, punctuation cleaning, stemming
- **Word Cloud Generation**: Visual representation of most common terms
- **Topic Modeling**: LDA (Latent Dirichlet Allocation) for discovering review topics
- **N-gram Analysis**: Bigram frequency analysis for cuisine combinations

### 🎯 Machine Learning & Clustering
- **K-Means Clustering**: Group restaurants based on cost, rating, and cuisine features
- **Feature Engineering**: Multi-label binarization for cuisine categories
- **Cluster Analysis**: Identify restaurant segments and their characteristics
- **Visualization**: Interactive plots using Plotly and static plots with Matplotlib/Seaborn

## Dataset
The project uses two main datasets:
1. **Zomato Restaurant Metadata** (`Zomato Restaurant names and Metadata.csv`)
   - Restaurant names, costs, cuisines, collections
2. **Zomato Restaurant Reviews** (`Zomato Restaurant reviews.csv`)
   - Customer reviews, ratings, reviewer information

## Installation

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Setup
1. Clone or download the project files
2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Download NLTK data (run once):
```python
import nltk
nltk.download('stopwords')
```

## Usage

1. **Start Jupyter Notebook**:
```bash
jupyter notebook
```

2. **Open the notebook**: `ML_Project.ipynb`

3. **Run cells sequentially** to:
   - Load and explore the datasets
   - Perform data cleaning and preprocessing
   - Generate visualizations and word clouds
   - Conduct sentiment analysis
   - Build clustering models
   - Analyze results

## Project Structure
```
ML_Project/
│
├── ML_Project.ipynb          # Main analysis notebook
├── requirements.txt          # Python dependencies
├── README.md                # Project documentation
├── .gitignore               # Git ignore file
│
└── data/ (not included in repository)
    ├── Zomato Restaurant names and Metadata.csv
    └── Zomato Restaurant reviews.csv
```

## 📋 **Data Requirements**
**Note**: The datasets are not included in this repository. To run the analysis, you'll need:
1. `Zomato Restaurant names and Metadata.csv`
2. `Zomato Restaurant reviews.csv`

Place these files in a `data/` folder in the project root.

## Key Analysis Results

### Restaurant Insights
- **Cost Analysis**: Identification of premium vs. budget-friendly restaurants
- **Cuisine Popularity**: Most common cuisine combinations and regional preferences
- **Collection Analysis**: Popular restaurant categories and collections

### Review Insights
- **Sentiment Distribution**: Overall sentiment patterns in customer reviews
- **Rating Correlation**: Relationship between numerical ratings and sentiment scores
- **Reviewer Patterns**: Analysis of top contributors and their rating behaviors

### Clustering Results
- **5 Restaurant Clusters**: Based on cost, rating, and cuisine features
- **Cluster Characteristics**: Each cluster represents different restaurant segments
- **Business Insights**: Actionable insights for restaurant positioning and strategy

## Technologies Used

- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly, WordCloud
- **NLP**: NLTK, TextBlob, Gensim
- **Machine Learning**: Scikit-learn
- **Topic Modeling**: LDA (Latent Dirichlet Allocation)
- **Interactive Visualization**: pyLDAvis

## Key Visualizations

1. **Word Clouds**: Most frequent terms in reviews and restaurant names
2. **Sentiment Scatter Plots**: Polarity vs. Subjectivity analysis
3. **Cluster Visualization**: Restaurant segments based on multiple features
4. **Heatmaps**: Missing data patterns and correlation analysis
5. **Interactive LDA**: Topic modeling visualization




## License
This project is for educational and research purposes.

---
*Created for restaurant data analysis and customer sentiment insights*
