---
layout: post
title: "Machine Learning"
date: 2022-05-09
excerpt: "Machine Learning Projects by Sihan Min"
tags: [machine learning]
project: true
comments: false
---

### Node Embedding for Large-Scaled Knowledge Graph
* Feb 2020 – Apr 2020
* Discovered a better embedding method for nodes from a large-scale, real-world Knowledge Graph named YAGO, and completed various downstream tasks such as link prediction and node classification using PyTorch framework.
* Initialized nodes with TransE embedding, sampled balanced subgraph based on edge-type and neighborhood, and fed subgraphs into mini batches to train a Relational Graph Convolutional Network (RGCN) with embedding output.

### Skull Stripping Using Semi-Supervised Deep Learning
* Apr 2019 - June 2019
* Developed an automatic segmentation solution for brain MRI to keep the essential tissue with deep learning models.
* Employed OSVOS model with Tensorflow using fully convolutional neural network (FCN): pre-trained parent network for basic foreground segmentation; fine-tuned the network on ground truth image pairs to minimize pixel-wise cross entropy loss.
* Used less than 20 sets of segmented MRI, and got over 90% accuracy in pixel-wise comparison on testing sets.

### Movie Recommendation by Rating Prediction
* Jan 2019 - Mar 2019
* Built personalized recommendation system using user movie ratings with multiple machine learning methods in Python.
* After experiments on different model combinations, used ensemble of two best models to predict user rating: SVD model on user movie pairs’ ratings and user-based Linear Regression with movie tags information.
* Achieved root MSE of 0.822 on over 4,000,000 user-movie pairs in final rating prediction.

### Political Sentiments Analysis on Reddit Text
* Apr 2018 - June 2018
* Aggregated people’s attitudes towards the two Parties and Donald Trump by NLP on Reddit posts and comments.
* Fit tokenized and lemmatized sentences from Reddit text into Machine Learning model (Logistic Regression) in Python, which learns to label sentiments of positive/negative towards two parties and Donald Trump.
* Combined queries to MySQL database, and visualized clear political sentiments fluctuation over states in time
series graph with R.
