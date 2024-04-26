---
name: News Classification Dataset
desc: A dataset consisting of news articles categorized into different topics.
language:
- en
dimension:
- text
- understanding
sub_dimension:
- news
- category-classification
github: https://github.com/hopecommon/compasshub_news_classification_dataset.git
release_date: 2024-04-26
tag:
- text
- classification
- news
---
## Introduction
This dataset is designed to evaluate the performance of large models on the task of news article classification. It contains a diverse range of news articles from various categories, each labeled with its respective topic.

## Meta Data
You can download from github: https://github.com/hopecommon/compasshub_news_classification_dataset.git
.The dataset includes the following fields for each entry:
- `title`: The headline of the news article.
- `content`: The full text of the news article.
- `category`: The category to which the news article belongs.

## Example
Here is an example of a record in the dataset:
```json
{
  "title": "Economy grows by 2% in Q1",
  "content": "The economy has seen a growth of 2% in the first quarter...",
  "category": "Economy"
}