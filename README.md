# Discrete Probability Detector (DPD)
Discrete Probability Detector (DPD) is an algorithm that transforms any sequence of symbols into a transition matrix. The algorithm may receive special characters from the entire ASCII range. These characters can be letters, numbers or special characters (ie. <kbd>`7Eu9f$*"</kbd>). The number of symbol/character types that make up a string, represent the number of states in a Markov chain. Thus, DPD is able to detect the number of states from the sequence and calculate the transition probabilities between these states. The final result of the algorithm is represented by a transition matrix (square matrix) which contains the transition probabilities between these symbol types (or states). The transition matrix can be further used for different prediction methods, such as Markov chains or Hidden Markov Models. This version of DPD is made in <kbd>HTML/JavaScript/CSS</kbd>.

Live demo: https://gagniuc.github.io/Discrete-Probability-Detector-JS/

![screenshot](https://github.com/Gagniuc/Discrete-Probability-Detector-DPD-/blob/main/%5BG%5D%20Discrete%20Probability%20Detector.png)
