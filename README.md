# TensorFlow-Implementations

This repository contains the projects I have done with TensorFlow, and includes a few tutorials.

TensorFlow / Deep Learning Tutorial:
These are the files I have created to teach others Deep Learning:
- MLP.pdf / MLP Part 2.pdf / CNN.pdf
- Linear Regression in TensorFlow.ipynb
- Fashion MNIST in TensorFlow.ipynb (Adapted from https://www.coursera.org/learn/introduction-tensorflow Week 1 Notebook)
- Fashion MNIST (CNN) in TensorFlow.ipynb
- Custom Training Loop: Converts a simple Keras model.fit into an expanded customizable training loop using GradientTape. Includes graph plotting and model visualization utilities. 

Below are the projects I have done using TensorFlow:
- Text Generation: Compares RNN vs a Markov Chain method to generate text. Surprisingly, both are around the same, just by using like n=5 previous characters to predict the next one for the Markov Chain method.
- Text Generation for Code: Compares RNN vs a Markov Chain method to generate text for coding (and also news). Markov Chain methods generate better text, and that could be due to a very small dataset used. Datasets: news.txt, coding.txt
- Wordle: Solves the Wordle game using 5 different agents: Random (baseline), Minimize Worst Outcome, Maximize Entropy (Information Theory), Minimize Variance, Minimize Variance and Worst Outcome. Currently there are only algorithmic agents. In the future, there will also be Deep Q-Networks and Actor-Critic models.
