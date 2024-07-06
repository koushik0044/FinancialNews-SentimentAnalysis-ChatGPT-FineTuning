# Financial News Sentiment Analysis using ChatGPT-3.5 Turbo

This repository contains a Jupyter Notebook where ChatGPT-3.5 Turbo is fine-tuned for sentiment analysis on financial news articles. The notebook also compares the fine-tuned model's performance against zero-shot and few-shot prompting methods.

## Dataset

The dataset used for this project is the "Sentiment Analysis for Financial News" dataset available on Kaggle. It includes financial news headlines from different news sources, labeled with sentiments as positive, neutral, or negative.

[Dataset Link](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news/data)

## Setup

To run the notebook, you need to set up a Python environment and install the necessary libraries. Follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/koushik0044/FinancialNews-SentimentAnalysis-ChatGPT-FineTuning.git
   ```
2. Navigate to the repository directory:
   ```
   cd FinancialNews-SentimentAnalysis-ChatGPT-FineTuning
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Notebook

You can run the Jupyter Notebook by launching Jupyter in your terminal:
```
jupyter notebook
```
Navigate to `Fine-Tuning.ipynb` and run the cells sequentially to observe the model training and evaluations.

## Notebook Sections

- **Data Loading and Preprocessing**: Load the dataset and prepare it for model training.
- **Model Fine-tuning**: Fine-tune ChatGPT-3.5 Turbo on the sentiment analysis task.
- **Model Evaluation**: Compare the fine-tuned model's performance to baseline models using zero-shot and few-shot techniques.
- **Results and Discussion**: Discuss the results and implications of the fine-tuning and comparison.

## Contributions

Feel free to fork this repo and submit pull requests with improvements or file issues if you encounter any problems.

Thank you for checking out this project!
