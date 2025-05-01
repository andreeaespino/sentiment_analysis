# Hotel Industry Sentiment Analysis Dashboard
This repository contains Python notebooks for performing and visualizing sentiment analysis in the hotel industry. It includes data processing, sentiment classification, and an interactive prototype dashboard to explore customer feedback and trends.

## Dataset Information
The hotel reviews used in this project are sourced from the OpinRank Review Dataset, which compiles full customer reviews collected from TripAdvisor. The dataset covers hotels in 10 major cities, with each city containing approximately 80 to 700 hotels. In total, the dataset includes 254,571 reviews, providing a rich and diverse base for sentiment analysis and insights into customer experiences across a wide range of hotel services and locations.

## Technologies
The project is created with:
* `python`
* `pandas`
* `numpy`
* `re`
* `nltk`
* `scikit-learn`
* `torch`
* `transformers`
* `gradio`

## Contents
- **`notebook.ipynb`**: Core notebook for sentiment analysis, including data loading, text preprocessing, sentiment classification using VADER (Valence Aware Dictionary and sEntiment Reasoner), RoBERTa (Robustly optimized BERT approach), and LDA (Latent Dirichlet Allocation).
  
- **`prototype.ipynb`**: Contains the Gradio-based dashboard prototype, allowing users to interactively explore sentiment insights across different hotel services, locations, or time periods.

## Features
- Automatic sentiment classification of customer reviews
- Visual and interactive sentiment breakdown (positive, negative, neutral)
- Gradio interface for quick deployment and interaction
- Insight filtering by hotel, city, or review time

## Getting Started

### Prerequisites

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn vaderSentiment torch transformers gradio
```
### Running Notebooks
1. Clone the repository:
```bash
git clone https://github.com/andreeaespino/sentiment_analysis.git
cd sentiment_analysis
```
2. Launch Jupyter Notebook:
```bash
jupyter notebook
```
3. Open and run:
   
* `notebook.ipynb` to analyze sentiment data.
* `prototype.ipynb` to launch the Gradio dashboard.

## Acknowledgements
- NLP tools: NLTK, Scikit-learn
- Gradio for interactive app building

## Contact
Created by Liz Andrea Espino Cantera, GitHub: @liz4ndr34
