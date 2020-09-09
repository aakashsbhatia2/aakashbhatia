---
layout: page
title: Projects
subtitle: 
---

<head>
    <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-175479624-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-175479624-1');
</script>
</head>
<h3>Detecting Deceptive Hotel Reviews</h3>
This project is a re-implementation of the paper [Finding Deceptive Opinion Spam by Any Stretch of the Imagination](https://www.aclweb.org/anthology/P11-1032/). Here, I developed machine learning models to classify honest and deceptive reviews for the top 20 hotels in Chicago. The hotel reviews were obtained from TripAdvisor.
- Dataset: The dataset consisted of 400 truthful and 400 deceptive hotel reviews.
- Algorithms used: Support Vector Machines, Naive Bayes
- Language encodings used: Uni-gram, Bi-gram, Tri-gram. The Bi-gram and Tri-gram representations consumed the prior n-gram notation as well.
- Technologies used: Python
- Libraries used: [Scikit-Learn](https://scikit-learn.org/stable/), [NLTK](https://www.nltk.org/)
- You may view the code for this project on GitHub [here](https://github.com/aakashsbhatia2/Deception-detection)

<hr /> 

<h3>Interactive Visual Dashboard for Road Accidents in the United States</h3>
In this project, I developed a concise, interactive, single-screen visual dashboard using Python and d3.js to study the effects of weather conditions on road accidents within the United States.
- Dataset: The dataset contained statistics of road accidents with the United States. This dataset was obtained from Kaggle. The dataset can be found [here](https://www.kaggle.com/sobhanmoosavi/us-accidents)
- Technologies used:
    - JavaScript: I used d3.js to create the visualisations
    - Python: A Flask Server to host the dashboard, perform operations on the data (Principal Component Analysis, k-means clustering), render updated data to the dashboard.
    - HTML, CSS: To create the webpage containing the visualisations
- Data Science Techniques used: 
    - Principal Component Analysis: I performed dimension reduction using PCA to generate a scatter-plot matrix of the top 2 PC vectors.
    - Stratified Sampling using k-means clustering: To project the data onto a parallel Co-ordinate chart, I performed stratified sampling using k-means clustering. This allowed me to reduce the number of datapoints being projected while maintaining the data distribution.
- Libraries Used: [Scikit-Learn](https://scikit-learn.org/stable/), [d3.js](https://d3js.org/), [Flask](https://pypi.org/project/Flask/)
- You may view the code for this project on GitHub [here](https://github.com/aakashsbhatia2/Visualization-Project)

<hr /> 

<h3>Machine Learning Algorithms from scratch </h3>
In this project, I implemented 5 machine learning algorithms from scratch (i.e. WITHOUT [Scikit-Learn](https://scikit-learn.org/stable/)). The algorithms I implemented are:
- Perceptron:
    - I implemented the perceptron algorithm from scratch using Python. My implementation can be found on GitHub [here](https://github.com/aakashsbhatia2/Perceptron-AdaBoost)
- Adaptive Boosting (AdaBoost):
    - I implemented Adaptive Boosting from scratch using Python. 
    - I used decision stumps as the weak learners for my implementation
    - My implementation can be found on GitHub [here](https://github.com/aakashsbhatia2/Perceptron-AdaBoost)
- Support Vector Machines (SVM):
    - I implemented Support Vector Machines from scratch using Python.
    - I used stocastic gradient decent optimization for my implementation of SVM.
    - My implementation can be found on GitHub [here](https://github.com/aakashsbhatia2/Support-Vector-Machine)
- K-means Clustering:
    - I implemented the k-means clustering algorithm from scratch using Python.
    - I used Euclidean distance, Manhattan distance and Minkowski distance metrics for my implementation
    - My implementation can be found on GitHub [here](https://github.com/aakashsbhatia2/k-means)
- K-nearest Neighbors:
    - I implemented the k nearest neighbors algorithm from scratch using Python 
    - My implementation can be found on GitHub [here](https://github.com/aakashsbhatia2/K-Nearest-Neighbors)


<hr /> 

<h3>COVID-19 Data Analysis using Hadoop and Spark</h3>
In this project, I used Hadoop and Spark to analyse a COVID-19 dataset. 
- I performed 3 tasks:
    - Obtain the number of cases per country and world-wide
    - Obtain the number of cases per country and world-wide for a given time period
    - Obtain country-wise number of cases per million
- Technologies used: [Hadoop](https://hadoop.apache.org/), [Spark](https://spark.apache.org/), Java
- My implementation can be found on GitHub [here](https://github.com/aakashsbhatia2/COVID-19-Analytics)