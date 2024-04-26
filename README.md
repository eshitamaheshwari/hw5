# Neural Exploration Homework Guide: Question Category Predicting Tool

## Overview
The goal of my project is to predict categories for Quiz Bowl questions. It uses Pytorch and NN models to predict the category of each of the question texts.

## How to Get Started
In order to run this model, you will need Python 3+ installed. You need to clone this repository onto your computer and access it through an IDE like VSCode. You will also need to install the libraries that are in the requirements.txt file. You can download all the libraries in the requirements.txt file by doing:
`pip install -r requirements.txt`
Additionally, you should have the files `qanta.buzztrain.json` and `qanta.guesstrain.json` in the data directory and you can change the path in the preprocessing portion of the code to match where the files lie on your computer.

## How to Run the Model
You can start the process of training the model by doing:
`python classname.py` 
In this case, the file name is `processing.py`.

## How to Evaluate this Model
You can evaluate this model by using accuracy metrics during training.

