# Seasons of Code (SOC) - Project ( May 2022 - July 2022)
This repository contains the code for the project I completed for the Seasons of Code 2022, hosted by Web and Coding Club, IIT Bombay.

# MUSIFY- Music-Composition-Using-AI
This repository has been developed to build a model that takes existing music data as input learns the pattern and generates "new" music.
The model-generated music need not be professional, as long as it is melodious and good to hear.

## Learning Objective
* To compose the music anyone need not to be expert even the non-musician like me can also generate the music using the deep learning concepts.
* General idea of concept of Automatic Music Generation for processing a short piece of music with minimum human intervention.
* The objective of the project is to explore the deep learning field and compose the music using artificial intellgence .
* This project case particulary focuses on the LSTM and RNN for the music generation.

## What is Music ?
* Music as a collection of tones of different frequencies.
* Input- Sequence of musical events/notes.
* Output- New sequence of musical events/notes.

## File Structure
* **All Midi Files** -> This is the dataset zip folder containing various midi files of different composers.
* **music_composition_code.ipynb** -> In this file, we will build, train and test our model.
* **Composed_music_output.mid** -> This is a music file of predicted notes.


## Built with
* ipython-notebook - Google Colab 
* numpy, scipy- number python library
* pandas - data handling library
* Keras - Deep Learning Library
* **Dataset** : https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi

## Notebook Implementation
* Importing required Libraries
* Reading Musical Files
* Data Preparation
* Build LSTM model
* Hyperparameter tuning.
* Run the last cell and a file named as Composed_music_output.mid will be saved
* Playing the saved file 
## Acknowledgements

 - [LSTMs for Music Generation](https://towardsdatascience.com/lstms-for-music-generation-8b65c9671d35)
 - [Want to Generate your own Music using Deep Learning?](https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/)
 - [Music Generation Using Deep Learning](https://medium.com/mlearning-ai/music-generation-using-deep-learning-49692851c57c)

## Authors

- [@saurabhbaghele](https://github.com/saurabhbaghele)
