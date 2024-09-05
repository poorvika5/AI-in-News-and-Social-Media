<h1 align="center">Sentiment Analysis of AI in News and Social Media</h1>

[![Project Overview](/images/project_overview.png)](https://github.com/your_username/sentiment-analysis-ai)

This project focuses on sentiment analysis using natural language processing (NLP) techniques to understand public opinion on AI through the analysis of news and social media data. The analysis leverages advanced models like BERT to detect sentiment related to specific aspects of the text.

## Built With

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [NLTK](https://www.nltk.org/)
- [BERT (via Hugging Face Transformers)](https://huggingface.co/transformers/)
- [Jupyter Notebook](https://jupyter.org/)
- [Google Colab](https://colab.research.google.com/)

## Getting Started

To learn more on this project, follow these steps:

### Prerequisites

Ensure you have a Google account and access to Google Colab, as well as the necessary Python packages.

### Opening the Project in Google Colab

1. Clone the repository or download the notebook:

    ```bash
    git clone https://github.com/poorvika5/sentiment-analysis-ai.git
    ```

2. Open the notebook in Google Colab:

    - Go to [Google Colab](https://colab.research.google.com/).
    - Click on `File > Upload notebook`.
    - Select the notebook file from your cloned repository.

3. Alternatively, you can open the notebook directly in Google Colab by clicking on this badge:

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ManishAshok/sentiment-analysis-ai/blob/main/Group_Project_ (1).ipynb)

## Project Objectives

### Objective 1: Sentiment Analysis Using NLP

The project aims to conduct sentiment analysis on AI-related topics in news and social media. The analysis involves data preprocessing, sentiment detection, and visualization of trends.

### Objective 2: Advanced NLP Models

The project utilizes advanced NLP models like BERT for aspect-based sentiment analysis, enabling a deeper understanding of specific sentiments related to different aspects of AI.

### Objective 3: Data Visualization

Visualizations are created to illustrate the sentiment trends and insights drawn from the analysis.

## Data Visualization

The project includes various visualizations to illustrate the findings:
<p align="center">
  <img src="/images/channel_distribution_cleaned.png" alt="Sentiment Trends" width="600"/>
</p>
<p align="center">
  <img src="/images/articles_over_time_cleaned.png" alt="Sentiment Trends" width="600"/>
</p>
<p align="center">
  <img src="/images/wordcloud_headlines_cleaned.png" alt="Sentiment Trends" width="600"/>
</p>
<p align="center">
  <img src="/images/sentiment_trends.png" alt="Sentiment Trends" width="600"/>
</p>

<p align="center">
  <img src="/images/aspect_sentiment.png" alt="Aspect-Based Sentiment Analysis" width="600"/>
</p>

## Roadmap

- [x] Data Collection and Preprocessing
- [x] Sentiment Analysis using NLP
- [x] Visualization of Sentiment Trends
- [ ] Model Refinement and Real-Time Analysis
- [ ] Cross-Lingual Sentiment Analysis

## Contributing

Contributions are welcome! Please follow the standard procedure to contribute.

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


## FAQs

<details>
  <summary>How do I update the dataset?</summary>
  
  Replace the existing dataset with a new one in the same format, and rerun the analysis steps in Google Colab. Adjust any relevant parameters in the analysis to accommodate changes in the data structure or size.
</details>

<details>
  <summary>Can I use this analysis for other topics?</summary>
  
  Yes, you can adapt the analysis for other topics by modifying the code to suit the new data. Ensure that the dataset is cleaned and formatted similarly before applying the existing code.
</details>
