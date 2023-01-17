# TensorFlow-Implementations

This repository contains the projects I have done with TensorFlow, and includes a few tutorials.

Check out my Youtube channel which uses some of this material for lessons.

Other social media sites:

Youtube: https://www.youtube.com/channel/UCgRNCT8mrzKYebyG3Ao9DJA/videos

Twitch:  https://www.twitch.tv/johncm99 

AI Blog: https://delvingintotech.wordpress.com/

LinkedIn: https://www.linkedin.com/in/chong-min-tan-94652288/

Twitter: https://twitter.com/johntanchongmin

TensorFlow / Deep Learning Tutorial:
These are the files I have created to teach others Deep Learning:
- MLP.pdf / MLP Part 2.pdf / CNN.pdf / RNN.pdf / Transformer.pdf / GNN.pdf
- AlphaGo:Zero.pdf
- Geometric Deep Learning.pdf (Summary and personal insights of Geometry Deep Learning proto-book https://geometricdeeplearning.com/ by Michael M. Bronstein, Joan Bruna, Taco Cohen, Petar Veličković)
- Linear Regression in TensorFlow.ipynb
- Fashion MNIST in TensorFlow.ipynb (Adapted from https://www.coursera.org/learn/introduction-tensorflow Week 1 Notebook)
- Fashion MNIST (CNN) in TensorFlow.ipynb
- GAT_GCN_node_classification.ipynb: Graph Neural Network implementation using TensorFlow on Cora Dataset
- Tutorial_RNN_Text_Generation.ipynb
- Custom Training Loop: Converts a simple Keras model.fit into an expanded customizable training loop using GradientTape. Includes graph plotting and model visualization utilities. 
- GPT_Demo: Uses huggingface GPT-2 model for text generation, as well as Bertviz for attention visualization

Paper_Reviews Folder:
- Overview: Documents Interesting Deep Learning / Machine Learning Papers
- Decision Transformers.pdf
- GATO.pdf
- Policy Graident Presentation.pdf
- AlphaTensor Presentation.pdf

RL Folder:
- Overview: Documents Reinforcement Learning Experiments and Tutorials
- RL Part 1.pdf, DQN.pdf
- MCTS.ipynb: Using Monte Carlo / Monte Carlo Tree Search / Value Estimates to solve the game of Nim
- Cart Pole.ipynb: Using rule-based and DQN to solve Cart Pole

Below are the projects I have done using TensorFlow (in Implementations folder):
- Text Generation: Compares RNN vs a Markov Chain method to generate text. Surprisingly, both are around the same, just by using like n=5 previous characters to predict the next one for the Markov Chain method.
- Text Generation for Code: Compares RNN vs a Markov Chain method to generate text for coding (and also news). Markov Chain methods generate better text, and that could be due to a very small dataset used. Datasets: news.txt, coding.txt
- If-Else (Part 1): Investigates if a neural network can model if-else statements
- Wordle: Solves the Wordle game using 5 different agents: Random (baseline), Minimize Worst Outcome, Maximize Entropy (Information Theory), Minimize Variance, Minimize Variance and Worst Outcome. Currently there are only algorithmic agents. In the future, there will also be Deep Q-Networks and Actor-Critic models.
