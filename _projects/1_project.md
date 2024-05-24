---
layout: page
title: Toxicity Classification (Kaggle) 
description: Bronze medal(Top 10%)
img: assets/img/jigsaw.png
importance: 1
category: AI
# related_publications: einstein1956investigations, einstein1950meaning
---

[Jigsaw Unintended Bias in Toxicity Classification(Kaggle)                                                                 ](https://www.kaggle.com/competitions/jigsaw-unintended-bias-in-toxicity-classification/code?competitionId=12500&sortBy=dateRun&tab=profile&excludeNonAccessedDatasources=false)

<h3> Challenge: </h3>
The Conversation AI team, a research initiative founded by Jigsaw and Google (both part of Alphabet), builds technology to protect voices in conversation. A main area of focus is machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion.
This competition is aimed to solve the problem of identifying toxicity across diverse online conversations by building a NLP-based model to recognize toxicity and minimize this type of unintended bias with respect to mentions of identities.

<h3> Solution: </h3>
- Cleaned and regularized the data for model construction by using the deep model BERT and LSTM for a jointly learning and prediction.
- Preprocessed natural language data by leveraging word2vec and glove to transform them into text embeddings.
- Set up and experimented advanced NLP models, including BI-LSTM, BERT, GPT-2, and XLNet. Based on our experiment results, we chose the blend of BI-LSTM training and BERT fine-tuning in our method.