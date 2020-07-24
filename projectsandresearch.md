---
layout: page
title: Projects
subtitle: 
---

<h3>Detecting Deceptive Hotel Reviews</h3>
This project is a re-implementation of the paper [Finding Deceptive Opinion Spam by Any Stretch of the Imagination](https://www.aclweb.org/anthology/P11-1032/). Here, I developed machine learning models to classify honest and deceptive reviews for the top 20 hotels in Chicago. The hotel reviews were obtained from TripAdvisor.
- Dataset: The dataset consisted of 400 truthful and 400 deceptive hotel reviews.
- Algorithms used: Support Vector Machines, Naive Bayes
- Language encodings used: Uni-gram, Bi-gram, Tri-gram
- Technologies used: Python
- Libraries used: [Scikit-Learn](https://scikit-learn.org/stable/), [NLTK](https://www.nltk.org/)
- You may view the code for this project on GitHub [here](https://github.com/aakashsbhatia2/Deception-detection)

<hr /> 

<h3>Interactive Visualisation of Road Accidents in the United States</h3>
In this project, I developed concise, interactive, single-screen visual dashboard using Python and d3.js to study the effects of weather conditions on road accidents within the United States.
- Dataset: The dataset contained statistics of road accidents with the United States. This dataset was obtained from Kaggle. The dataset can be found [here](https://www.kaggle.com/sobhanmoosavi/us-accidents)
- Technologies used:
    - JavaScript: I used d3.js to create the visualisations
    - Python: A Flask Server to host the dashboard, perform operations (Principal Component Analysis, k-means clustering), render updated data to the dashboard.
    - HTML, CSS: To create the webpage containing the visualisations
- Data Science Techniques used: 
    - Principal Component Analysis: I performed dimension reduction using PCA to generate a scatter-plot matrix of the top 2 PC vectors.
    - Stratified Sampling using k-means clustering: To project the data onto a parallel Co-ordinate chart, I performed stratified sampling using k-means clustering. This allowed me to reduce the number of datapoints being projected while maintaining the data distribution.
- Libraries Used: [Scikit-Learn](https://scikit-learn.org/stable/), [d3.js](https://d3js.org/), [Flask](https://pypi.org/project/Flask/)
- You may view the code for this project on GitHub [here](https://github.com/aakashsbhatia2/Visualization-Project)
