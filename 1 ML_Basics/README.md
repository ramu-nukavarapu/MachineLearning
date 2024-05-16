# 1 ML Basics

# AI vs ML vs DL

![AI vs ML vs DL](1%20ML%20Basics/Untitled.png)

## Artificial Intelligence

- Artificial Intelligence is a branch in computer science that concerns with building smart & intelligent machines where the machine can make decisions by itself

## Machine Learning

- Machine Learning is a subset of AI where a machine is trained from the data and make predictions without explicitly programmed

## Deep Learning

- Deep Learning is a subset of ML that uses Artificial Neural Networks to learn from the data
- ANN  consists of three layers input layer, output layer and hidden layer(s)
- Each layer contains neurons that are similar to human neurons that goal is to mimic the human brain and perform complex computational tasks
- The main difference between ML and DL, In ML we should specify which is important and which is not (Feature Extraction). whereas, In DL don’t need to extract the features, the neurons will implicitly extract the features

---

## Types of Machine Learning

- There are mainly three types of machine learning:
    - Supervised Learning
    - Unsupervised Learning
    - Reinforcement Learning

### Supervised Learning

- In supervised learning, the ML algorithm learns from labelled data
- where the model learns  patterns and relationships between input data and corresponding labels using labelled data
- which tells us what kind of output we get for the given input

### Types of Supervised Learning

- There are two types in supervised learning:
    - **Classification -** classification is about predicting classes or discrete values
        - Classification algorithms: Random Forest, Decision Tree, KNN, Naïve Bayes
    - **Regression** - regression is about predicting numerical or continuous values
        - Regression algorithms: Linear Regression, Polynomial Regression

### Unsupervised Learning

- In unsupervised learning, the ML algorithm learns from unlabeled data
- where the model learns patterns and relationships between input data and corresponding labels without explicit guidance from labels (based on similarity)

### Types of Unsupervised Learning

- There are two types in unsupervised learning:
    - **Clustering** - involves in grouping the similar things
        - Clustering algorithms: k-means clustering, Hierarchal clustering
    - **Association** - used to find the important relationship between the data points
        - Association algorithms: Apriori, Eclat
    - **Principal Component Analysis (PCA)** - PCA is a dimensionality reduction technique used for data extraction and data visualizations

### Reinforcement Learning

- In reinforcement learning, the agent learns to make decisions by taking actions in environment and learns from the feedback
- the feedback is either reward (good) or penalty (bad)
- the goal is to maximize the reward over time