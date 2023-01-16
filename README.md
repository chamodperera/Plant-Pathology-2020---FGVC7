# Plant Pathology 2020 Competition - Residual Network Model

This repository contains the code for a residual network model used in the [Plant Pathology 2020 competition](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7) on Kaggle.

## Requirements
- Tensorflow 2.x
- Numpy
- Pandas
- Matplotlib
- Scikit-learn

## Data
The dataset used in this competition can be found on the [competition page](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data) on Kaggle.

## Model architecture
The model is based on the Residual Network architecture. It has been designed to make the training process more efficient by allowing the model to learn the residuals or differences between the input and output of a block.

The architecture consists of:

- input layer
- convolutional layer
- Residual blocks
- Average pooling layer
- Fully connected layers
- Output layer

## Training
The model was trained using the Adam optimizer with a learning rate of 0.001. The training was done for 20 epochs with a batch size of 64.

## Evaluation
The model achieved an accuracy of 91% on the validation set.

## Usage

- Clone this repository.
- Download the dataset from the Kaggle competition website and place it in the project's root directory.
- Install the required dependencies.
- Run the model.py file to train the model.
- Run the predict.py file to make predictions on new images.
