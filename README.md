LDA Topic Model on COVID-19 Continuous Lockdowns

This project implements Latent Dirichlet Allocation (LDA) to identify underlying topics from textual data related to continuous COVID-19 lockdowns. The dataset used consists of articles, reports, and social media discussions, focusing on the impact of the pandemic lockdowns across various domains such as health, economy, social behavior, and public policy.

Project Overview
As the world faced multiple lockdowns due to the COVID-19 pandemic, vast amounts of textual data were generated. This project aims to extract the major topics from such data using an LDA model. LDA is a popular generative probabilistic model used for topic modeling and discovering latent topics in large collections of text.

Features
Data Preprocessing:

Tokenization, stop word removal, and lemmatization.
Cleaning of text to remove special characters, URLs, and irrelevant content.
LDA Topic Modeling:

Latent Dirichlet Allocation (LDA) is used to discover hidden topics from the dataset.
Tuning of the number of topics using coherence scores.
Visualization:

Word clouds for each topic to highlight the most frequent terms.
Inter-topic distance map using pyLDAvis for model interpretation.
Evaluation:

Coherence scores to assess the quality of the model.
Manual interpretation of the generated topics based on real-world context.
Installation
