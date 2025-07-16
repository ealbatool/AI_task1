This repository contains a simple image classification project developed as part of my tarinig with smart methods. The model was trained using Teachable Machine by Google to distinguish between two classes: coffee and tea. The project includes a trained model in Keras (.h5) format, a Python script (executed on Google Colab) to test the model, and supporting documentation and output.

# Objectives
The main objectives of this task were:

Train an image recognition model using Teachable Machine with at least two classes.

Export the trained model in TensorFlow → Keras format.

Write a Python script to:

Predict and display the corresponding class.

# Tools and Technologies
Teachable Machine by Google

Python 3

TensorFlow

NumPy

Pillow (PIL)

Google Colab

# Model Training Process
Accessed Teachable Machine.

Created a new Image Project → Standard Image Model.

Added two classes: Coffee and Tea.

Uploaded relevant images to each class.

Trained the model using the default settings.

Exported the trained model in TensorFlow → Keras format (.h5).

Model Testing (Google Colab)
The Python script used to test the model was written and executed in Google Colab. Below is a summary of the key steps taken:

Uploaded the .h5 model and a test image to the Colab environment.

Used the model to predict the class of the input image.

# Results
The test image used was of tea.

The model successfully predicted the correct class: Tea.

A screenshot of the result is included in this repository.

# Repository Contents
model.h5 – Trained Keras model file

AI_task1.py – Google Colab notebook containing the testing code

test_tea.jpg – Sample input image used for testing

image.png – Screenshot of the output result

README.md – Project documentation
