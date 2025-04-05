# Sentiment Alignment of NYTimes Movie Reviews 🎥📰🤖
![image](https://github.com/user-attachments/assets/98bb7d5a-67ba-4223-9f02-0db89ad3f9ed)

This project analyzes sentiment alignment between professional critics and audience perspectives on movies, using the New York Times Movie Reviews API and advanced transformer-based models from Hugging Face.

The goal is to explore the relationship between professional movie reviews and audience sentiment, identifying where opinions align — and where they sharply diverge.

## 🚀 Project Overview

An end-to-end data pipeline combining:
- API data extraction
- Advanced natural language processing (NLP)
- Transformer-based sentiment analysis
- Comparative alignment analysis
- Data visualization and insights

## 🧩 Detailed Workflow

### 1. API Integration
- Used **NYTimes Movie Reviews API** to collect:
  - 🎥 Movie titles
  - 📝 Critics' reviews and highlights
  - ⏰ Publication dates
  - 🎯 Critics' Pick indicators
- Fetched and parsed JSON responses to create a clean dataset.

### 2. Data Preprocessing
- Structured API response into pandas DataFrame.
- Cleaned text:
  - Removed noise and irrelevant characters.
  - Standardized casing and punctuation.
- Prepared text fields for input to sentiment models.

### 3. Sentiment Analysis with Hugging Face 🤖
- Utilized **pre-trained Transformer model** from Hugging Face for robust sentiment classification.
- Passed both **Critics' reviews** and **Reader-facing summaries** through the model.
- Extracted probability scores and sentiment labels (positive / neutral / negative).

### 4. Sentiment Alignment Analysis
- Compared critic sentiments with audience-oriented summaries.
- Quantified alignment:
  - ✅ Cases where critics and readers shared sentiment.
  - ⚠️ Cases of disagreement.
- Computed alignment rate and analyzed sentiment gaps.

### 5. Visualization & Insights
- Created visual summaries:
  - Sentiment distribution histograms.
  - Critic vs. audience sentiment scatterplots.
  - Highlighted extreme divergence points.
- Derived actionable insights on public perception vs. critical acclaim.

### 6. Findings
- Identified movies with high alignment and divergence between professional reviews and audience sentiment.
- Observed sentiment patterns across genres and publication dates.
- Demonstrated the effectiveness of transformer models in nuanced sentiment detection.

## 📊 Tech Stack

- Python
- NYTimes Movie Reviews API
- pandas
- Hugging Face Transformers
- matplotlib, seaborn
- requests

## 📈 Results

- Achieved fine-grained sentiment analysis using Hugging Face models.
- Mapped sentiment alignment across dozens of movie reviews.
- Visualized sentiment divergences for actionable storytelling.

## 🚀 Future Enhancements

- Incorporate external sources like Twitter or Reddit for broader audience sentiment.
- Perform time-series analysis of sentiment changes pre/post-release.
- Deploy model insights to an interactive dashboard.
- Test multi-lingual sentiment models for broader review sets.
- Explore genre-based sentiment alignment trends.

## 🔑 API Disclaimer

This project uses the **NYTimes Movie Reviews API** and Hugging Face models for educational and research purposes.  
Always comply with the respective API and model licensing terms.
