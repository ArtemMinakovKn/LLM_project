# News Algorithmic Trading Strategy: LLM Approach
***Authors:*** *Artem Minakov, Elena Putilova, Diana Sharafeeva*

## Project goals 
This project explores the feasibility of using LLMs for algorithmic trading by analyzing news articles. It investigates how LLMs can enhance trading strategies based on news events, aiming to improve prediction accuracy and adaptability in dynamic market conditions.

## Data
Daily Financial News for 6000+ Stocks (gained by [Kaggle](https://www.kaggle.com/datasets/miguelaenlle/massive-stock-news-analysis-db-for-nlpbacktests/data)https://www.kaggle.com/datasets/miguelaenlle/massive-stock-news-analysis-db-for-nlpbacktests/data)

## Methodology 
Utilizing the 'Daily Financial News for 6000+ Stocks' dataset from Kaggle, containing 843,062 news events from Benzinga between 2010 and 2022, we focus on 50 S&P 500 companies with the most connected news events. Additionally, historical market data from Yahoo Finance for all S&P 500 stocks is collected to correlate news events with stock prices.

Large Language Models & Prompting Techniques:
Five LLMs representing encoder (BERT, RoBERTa, ELECTRA), decoder (Chat GPT-3.5 Turbo), and transformer (Flan-T5 Large) architectures are selected. Prompting techniques like few-shot and zero-shot are employed to guide models in making accurate predictions based on limited examples.

## Results
Encoders (BERT, RoBERTa, ELECTRA) show limited performance in classification, struggling to differentiate between positive, negative, and neutral classes.
Chat GPT-3.5 Turbo outperforms encoders, achieving modest accuracy and F1 scores in zero-shot mode for headlines and summarizations.
Flan-T5 Large demonstrates superior performance compared to proprietary models, achieving higher accuracy and F1 scores in zero-shot mode on headlines.

Incorporating LLMs into algorithmic trading strategies based on news events shows potential for improving prediction accuracy. While proprietary models like Chat GPT-3.5 Turbo yield consistent results, open-source models like Flan-T5 Large exhibit superior performance. Further research and refinement of prompting techniques are warranted to enhance the effectiveness of news-based trading strategies leveraging LLMs.
