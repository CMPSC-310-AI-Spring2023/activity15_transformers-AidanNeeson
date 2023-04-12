[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ymop5HUw)
# CMPSC 310 Activity 15

## Deadline: April 12 by 9:50am

## Assignment

 For this activity follow [Neural machine translation with a Transformer and Keras](https://www.tensorflow.org/text/tutorials/transformer).

## Submission

Submit completed Colab notebook showing generated output.

## Data

The data used in the tutorial is a data set that contains translations of text from English to Portuguese. It was preprocessed by being tokenized, breaking up the data into tokens and token ID's, numerical representations. This will group the text into words, phrases, subwords, or even characters. These tokens are then trimmed to always be shorter than a set maximum. It splits the target tokens into inputs and labels, where the at each input location the label is the next token ID.

## Transformer

A transformer model is a deep learning model that processes sequential input, all at once. This gives it the ability to utilize context to better make predictions about input text. This is due to the use of attention layers, crucial pieces of a transformer model, allowing access to states at any place throughout the sequence, giving the transformer model the ability to get and produce relevant information about tokens that are not close to where the transformer currently is in the sequence.

### Encoder



### Decoder

### Dense
