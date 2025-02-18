# Replication 1: Sentiment Analysis on Speeches

## Introduction

This is a repository for [*Sentiment Analysis with R: Natural Language Processing for Semi-Automated Assessments of Qualitative Data* by Klinkhammer (2022)](https://doi.org/10.48550/arxiv.2206.12649). The original paper presents a structured workflow for conducting sentiment analysis using **tidytext** in R, with a focus on visualizing sentiment trends in textual data.

Our replication primarily focuses on the application part. The original tutorial examines two simultaneous political speeches on the war in Ukraine. However, the corresponding datasets were not available in the associated [GitHub repository](https://github.com/statistical-thinking/sentiment-analysis/tree/main).

Given this limitation, we selected to compare two alternative speeches of political significance: **Donald Trump's victory speech** and **Kamala Harris' concession speech** from the 2024 U.S. presidential election.

## Main Contents

We replicate the **four visualizations** presented in the paper:

1.  **Keyword Frequency & Sentiments**
    -   Identifying the most frequent words and their associated sentiments.
2.  **Sentiment Distribution**
    -   The distribution of sentiments in NRC lexicon.
3.  **Intertemporal Use of Sentiments (Conditional Mean)**
    -   The conditional mean of word counts for all sentiment categories throughout the speech.
4.  **Intertemporal Sentiment Scores (Bing)**
    -   The sentiment scores throughout the speech, as measured by the Bing lexicon.

In addition, we compared the **Bing** and **VADER** lexicon in the 4th visualization. To examine the difference between the results made by using the two lexicons, we also conducted a validation by removing negations in Harris's speech.

## Conclusion and Contribution

This repository builds on [Dr. Dennis Klinkhammer's work](https://github.com/statistical-thinking/sentiment-analysis/tree/main), which provides a useful workflow of visualizing sentiments in text in different ways.

The contribution of our work is:

1.  **New data**
    -   We compared **Donald Trump's victory speech** and **Kamala Harris' concession speech** from the 2024 U.S. presidential election, fixing the issue of lack of data in the original repo and increasing the repulicability.
2.  **New dictionary**
    -   Rather than **Bing** used in the original work, we tried to improve the workflow by using **"VADER lexicon"** and compared the performance of two lexicons.

Overall, this is a repo that's suitable for freshmen in TAD to learn visualization associated with sentiment analysis.
