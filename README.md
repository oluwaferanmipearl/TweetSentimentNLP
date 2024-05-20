# Twitter Data Analysis Project

This project involves analyzing Twitter data to uncover insights into user demographics, tweet sentiments, and more. We explore the data, perform advanced natural language processing (NLP), and visualize the results to understand Twitter usage dynamics across different age groups.

## Dataset Description

The dataset consists of two main components:

- **Tweets:** This file includes the following fields:
  - `user_id`: ID of the user who posted the tweet.
  - `tweet_timestamp`: Timestamp of when the tweet was posted.
  - `tweet_text`: Text content of the tweet.

- **Users:** This file contains the following fields:
  - `user_id`: ID of the user.
  - `username`: Username of the user on Twitter.
  - `user_age`: Age of the user.
  - `followers`: List of user IDs who follow this user.

## Objectives

### Data Exploration

- Examine the structure and contents of the JSON file.
- Analyze statistics such as the distribution of follower counts, tweet frequency, and demographics (age groups).

### Feature Engineering

- Extract relevant features from the Twitter data, including:
  - `Follower count`
  - `Tweet content`
  - `Timestamps`

### Natural Language Processing (NLP) Analysis

#### Sentiment Analysis

- Utilize **TextBlob** for straightforward sentiment analysis.

#### Topic Modeling

- Use **Latent Dirichlet Allocation (LDA)** to identify common topics across tweets.
- Apply **N-gram models** to capture the context of words and improve sentiment analysis accuracy.
- Identify common topics or keywords used by users in each age group.

### Visualization

- Create visualizations to illustrate findings and insights derived from the data analysis.
- Visualize trends in follower counts, sentiment, and topic distribution across different age groups.

## Tools and Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical data processing.
- **Matplotlib**: For creating static, animated, and interactive visualizations in Python.
- **Seaborn**: For making statistical graphics.
- **NLTK**: For natural language processing tasks.
- **Scikit-learn**: For machine learning and predictive data analysis.
- **TextBlob**: For text processing tasks and sentiment analysis.

## Results and Discussion
## Follower Distribution


**Tweet Frequency**

![dee](https://github.com/oluwaferanmipearl/TweetSentimentNLP/assets/29439342/9f563700-e319-4eba-8d89-3365d8f693d3)

![p37](https://github.com/oluwaferanmipearl/TweetSentimentNLP/assets/29439342/d354d94b-ba3e-45c6-8cf1-f51111023093)

**Sentiment Analysis**

![p1](https://github.com/oluwaferanmipearl/TweetSentimentNLP/assets/29439342/93930be4-2e18-48c3-9bff-e83a177478a8)

![p2](https://github.com/oluwaferanmipearl/TweetSentimentNLP/assets/29439342/9d76776b-d328-462c-b5e9-8824c38bec97)

**Topic Modeling**

**Young**
![p3](https://github.com/oluwaferanmipearl/TweetSentimentNLP/assets/29439342/e924cf76-84b7-4ecb-8629-cc56a2e2d329)

**Old**
![p4](https://github.com/oluwaferanmipearl/TweetSentimentNLP/assets/29439342/f9743bd6-f19d-4260-9026-0ebfa16ea377)

## Conclusion
This project provides a comprehensive analysis of Twitter data, revealing how user behavior, sentiments, and interests vary across different age groups. The insights from this project can help understand social media dynamics and can be useful for targeted marketing, sentiment analysis, and user engagement studies.



