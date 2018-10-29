# Introduction
This project contains a notebook `machine_translation.ipynb` for the implementation of a deep neural network for an end-to-end machine translation pipeline for an English to French translation.

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.


## Amazon Web Services 

Please refer to the Udacity instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project. [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)

## Models
The code presented implemented and trained these three models:
- Simple RNN
- RNN with Embedding
- Bidirectional RNN
- Encoder-Decoder model
- Final model 

# Final model architecture
The final model is structured as follows:

  - 1 embedding layer
  - 2 Bidirectional RNN layers
  - Encoder-Decoder layer
  - 1 RNN
  - 1 fully connected layer
  learnigrate is 0.006
