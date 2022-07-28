# Seasons of Code (SOC) - Project
This repository contains the code for the project I completed for the Seasons of Code 2022, hosted by Web and Coding Club, IIT Bombay.

# MUSIFY- Music-Composition-Using-AI
This repository has been developed to generate a totally new piece of audio file (music) by training a LSTM network using a set of midi audio music files (piano notes).

## About the Project

* **Platform** : Colab Notebook
* **Language** : Python 3.8
* **Libraries Used** : Tensorflow, Music21, Keras, NumPy, Sklearn, tqdm
* **Dataset** : https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi

## Learning Objective
* General idea of concept of Automatic Music Generation with minimum human intervention.
* Learning various python libraries and packages including Numpy, Pandas, Tensorflow, json, os, Music21 
* Implementation of music generation using deep learning models such as LSTM and RNN.

## File Structure
* **All Midi Files/** : This is the dataset folder containing various midi files of different composers.
* **code.ipynb** : In this file, we will build, train and test our model.
* **MOD/** : This directory contains optimizer, metrics, and weights of our trained model.
* **AI_composed_music.mid** : This is a music file of predicted notes.

## Steps
Follow the steps and compose music using AI

* **STEP 1** : Download the files from the repository by clicking on **Code** button
* **STEP 2** : Install Libraries using pip command (In Anaconda Prompt)
* **STEP 3** : Open **code.ipynb** file using Jupyter Notebook / Visual Studio Code
* **STEP 4** : Run all the cells one by one and check the output
* **STEP 5** : Wait for the model training as it takes about 7-8 hours
* **STEP 6** : Run the last cell and a file named as **AI_composed_music.mid** will be saved
* **STEP 7** : Play the file **AI_composed_music.mid**
