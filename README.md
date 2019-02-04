# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Subreddit Classification

### Introduction
1. Using Reddit's API, collect posts from two subreddits: Communism & Socialism
2. Use NLP to train a classifier on which subreddit a given post came from.

---


### Executive Summary

#### Objective:
Use NLP and classification algorithms to distinguish between  two similar subreddit posts: Communism v. Socialism

#### Methodology:
* Query PushShift API to retrieve submissions
* Clean & pre-process text
* Vectorize / tokenized text
* Gridsearch to optimize hyper-parameters across two classification algorithms

#### Natural Language Processing:

1. Removed extraneous tags: ‘removed’ , moderator posts, hyperlinks, non-letter characters

2. Lemmatized text to reduce duplicates and better compare similarities

3. Vectorized data using TF-IDF:
* 75K vectors
* Removed  / edited stopwords
* N-Gram Range: (1, 2)

---

### Attachments

This analysis includes the following:
- A README markdown file that provides an introduction to and overview
- A two (2) Jupyter notebooks that describes the following: (1) API Query via PushShift API (2) Natural Language Processing and Model Selection Evaluation
- Accompanying presentation slideshow rendered as a .pdf file.

---

### Datasets

For this analysis, I leveraged PushShift API to query the following subreddits:

- [Communism Subreddit](https://www.reddit.com/r/communism/)
  * 74K Subscribers
- [Socialism Subreddit](https://www.reddit.com/r/socialism/)
  * 164K Subscribers


SOURCES:
Reddit / PushShift API

---

### Next Steps

1. Increase max features produced via TF-IDF Vectorization
2. Increase num of features considered in Random Forest

---
