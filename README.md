# Project3 
## Part of Udacity "Deep Learning Nanodegree Foundation Course" ##

Create a LSTM NN 
that will read 4000 lines of dialogue from the TV show "Simpsons" 
and then try to generate a "Simpsons-like" TV script.
The ambition is to train it on relatively few data to start with
and then if this works:
Train on the entire "Simpsons" dialogue which is available from Kaggle.


## Taken from the Notebook:
## TV Script Generation
In this project, you'll generate your own [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV scripts using RNNs.  
You'll be using part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons.  
The Neural Network you'll build will generate a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).

### Get the Data
The data is already provided for you.  
You'll be using a subset of the original dataset.  
It consists of only the scenes in Moe's Tavern.  
This doesn't include other versions of the tavern, like "Moe's Cavern", "Flaming Moe's", "Uncle Moe's Family Feed-Bag", etc..
