# Fake News Detection System

## Introduction

### Motivation
The grim reality is that there is a lot of misinformation and disinformation on the internet. The phenomenon of fake news is rapidly growing with the evolution of communication methods and social media. Fake news can be broadcast for various purposes: to increase site clicks, influence public opinion on political or financial matters, or even hinder public understanding. The widespread nature of fake news highlights the urgent need to verify news authenticity.

### Benefits of the Solution and Solution Uses
Machine Learning has the potential to combat fake news, despite its serious consequences. By detecting false information before it spreads, machine learning can mitigate the impact of fake news. Benefits of classifying fake news include:
- Enhancing media literacy and critical thinking, enabling individuals to distinguish between real and fake news.
- Protecting the public from the harmful effects of fake news, such as anxiety, confusion, and fear.
- Supporting the fact-checking and verification efforts of journalists, researchers, and authorities.
- Promoting the quality and integrity of news and information both online and offline.
- Fostering a more informed, engaged, and responsible citizenry.

## Datasets

### Dataset 1
- **Link**: [Onion or Not](https://www.kaggle.com/datasets/chrisfilo/onion-or-not/data)
- **Description**: Dataset of The Onion articles and real "Onion-like" news articles from the subreddit r/NotTheOnion. The Onion articles are labeled as 1, and the r/NotTheOnion articles are labeled as 0.
- **Columns**:
  - `text`: The headlines
  - `label`: 1 for Onion articles, 0 for r/NotTheOnion articles

### Dataset 2
- **Link**: [Fake News Detection](https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection)
- **Description**: Contains two .csv files, `fake.csv` and `true.csv`, including columns like text, subject, and date.
- **Columns**:
  - `title`: Title of the news
  - `text`: Description of the news
  - `subject`: Type or category of news
  - `date`: Date of the news publication
- **Note**: Labels will be assigned later after combining both .csv files.

### Dataset 3
- **Link**: [Fake News Dataset](https://www.kaggle.com/c/fake-news/data?select=train.csv)
- **Description**: Contains three .csv files; we will use `train.csv`.
- **Columns**:
  - `title`: Title of the news
  - `author`: Author of the news
  - `text`: Description of the news
  - `subject`: Type or category of news
  - `label`: 1 for potentially unreliable articles, 0 for reliable articles

## NLP Text Pre-processing Pipeline
![image](https://github.com/user-attachments/assets/af5df417-28eb-43a0-a639-c83df48793a6)

## Classification Models

### Naïve Bayes
Naïve Bayes is a probabilistic classifier inspired by Bayes' theorem, assuming that attributes are conditionally independent.

### Random Forest
Random Forest (RF) is an advanced form of decision trees (DT) and is a supervised learning model. It consists of a large number of decision trees working individually to predict an outcome, with the final prediction based on the class that receives the majority of votes.

### Support Vector Machine (SVM)
Support Vector Machine (SVM) is a popular supervised learning algorithm used for classification and regression problems. It is primarily used for classification tasks in machine learning.

