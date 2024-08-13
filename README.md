# Predicting the Composer of a Digital Music File

AAI-511 Team 7 Final Project

![image](https://github.com/user-attachments/assets/dfcb517e-c1da-4c32-bda5-f4aaf39884c5)


The objective of this project was to apply deep learning techniques to create a model that could process a piece of digital music and accurately classify the composer of the work to one four: Bach, Beethover, Mozart or Chopin.  Correctly classifying these works of music is a challenging task, as many composers are influenced by others, resulting in similarities in various characteristics of the music.  Due to the difficulty level of this particular genre, a successful outcome would indicate if such an approach was technically feasible and whether it could be generalized to other genres of music.

Dataset used: https://www.kaggle.com/datasets/blanderbuss/midi-classic-music/data

The model would need to process, understand and contextualize time-series piano roll sequences extracted from the midi file and accurately classify the composer based on these sequences.  To facilitate this, two model architectures were selected that are well suited to time-series analysis tasks: Long Short-term Memory (LSTM) and Convolutional Neural Network (CNN).  These models would be configured to process the piano roll sequences and run the result through a classification head that would output the composer prediction.  Multiple experiments were conducted to select the optimal model architecture, as will be explained in more detail below.


