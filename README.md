# Language Modeling with RNNs

Final project for the *Natural Language Understanding* course at University of Trento.

## Description

The goal of the assignment was to implement and evaluate a
Neural Language Model through a Recurrent Neural Network
of some kind. It is fairly ascertained that Neural Language Models
outperform N-gram Language Models in their ability to
capture long distance dependencies in word predictions, thanks
to the presence of hidden states in RNN cells and not being
limited by the upper bound N of N-gram’s span.

Specifically, the task consisted in implementing a baseline
RNN Language Model, consider its performance as a starting
point and then try to improve its strength and results by finetuning
it with any possible kind of techniques, such as regularization
or optimization procedures.

## Instructions for the execution of the code:

- We suppose to work with an existing directory with path "/content/gdrive/MyDrive/NLU_project/", 
  containing a folder "dataset" with the zipped dataset ptbdataset.zip (at "dataset/ptbdataset.zip") and an empty folder "models". 
- The code cells should be executed one after the other, in the same order in which they appear. 
  Otherwise some errors may arise in the execution.

