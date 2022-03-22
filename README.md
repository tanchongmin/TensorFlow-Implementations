# TensorFlow-Implementations

This repository contains the projects I have done with TensorFlow, and includes a few tutorials.

Use nbviewer for easy viewing and downloading.

- Custom Training Loop: Converts a simple Keras model.fit into an expanded customizable training loop using GradientTape. Includes graph plotting and model visualization utilities. 
- Text Generation: Compares RNN vs a Markov Chain method to generate text. Surprisingly, both are around the same, just by using like n=5 previous characters to predict the next one for the Markov Chain method.
- Text Generation for Code: Compares RNN vs a Markov Chain method to generate text for coding (and also news). Markov Chain methods generate better text, and that could be due to a very small dataset used. Datasets: news.txt, coding.txt
- Wordle: Solves the Wordle game using 5 different agents: Random (baseline), Minimize Worst Outcome, Maximize Entropy (Information Theory), Minimize Variance, Minimize Variance and Worst Outcome. Comes with guessdata.pickle which caches all the possible guess outcomes for the guess words and target words, and helps to speed up the agents.
