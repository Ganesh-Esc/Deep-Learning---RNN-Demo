# IMDB Sentiment Classification with Recurrent Neural Networks (RNNs)

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/)

A hands-on exercise in which we will build and train a "vanilla" Recurrent Neural Network (RNN) to perform binary sentiment classification on the IMDB movie review dataset. 🎬

---

## 📖 Lab Overview

This lab provides a step-by-step guide to building a neural network for a classic Natural Language Processing (NLP) task: **sentiment analysis**. We will use the well-known IMDB dataset, which contains 50,000 movie reviews labeled as either positive or negative.

Our tool of choice is a simple or "vanilla" **Recurrent Neural Network (RNN)**, an architecture specifically designed to handle sequential data like text.

The lab is structured in two parts:
1.  We will first walk through the complete process of data preparation and the construction of a baseline RNN model.
2.  Then, it will be your turn to experiment by building and tuning your own models to improve upon the baseline.

---

## 🔬 Core Concepts

* **Sentiment Analysis:** The process of computationally identifying and categorizing opinions expressed in a piece of text to determine whether the writer's attitude is positive, negative, or neutral.
* **Recurrent Neural Networks (RNNs):** Neural networks that are designed to work with sequence data. They process inputs one element at a time, maintaining an internal "state" or "memory" that captures information about what has been processed so far.
* **Word Embeddings:** A technique to represent words as dense numerical vectors. The `Embedding` layer in Keras is the first step in our model, turning positive integers (word indices) into dense vectors of fixed size.
* **Padding Sequences:** RNNs require inputs to have a consistent length. We will use padding to ensure all review sequences are the same size before feeding them into the model.

---

## 🎯 Learning Objectives

After completing this lab, you will be able to:

1.  Load and prepare a text dataset for deep learning using the Keras API.
2.  Understand the necessity of padding sequences for RNNs.
3.  Build a `Sequential` Keras model containing `Embedding`, `SimpleRNN`, and `Dense` layers.
4.  Train and evaluate a text classification model.
5.  Experiment with different model architectures and data preparation techniques to improve performance.

---
