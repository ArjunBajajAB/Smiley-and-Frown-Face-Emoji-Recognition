#Smile Recognition
#First Edition

## Overview

The program opens a window in which the user can draw a smiley face or a frown face and the program captures the face drawn by the user and predicts the drawn face.

## Open Source Model
Python Library

1. Opencv
2. Keras
3. Tkinter
4. Numpy
5. Pyscreenshot
6. Tensorflow 

## Design and procedure for execution

The project is written in a python file.

	1.python Smiley_Recognition.py
	2. There are 5 buttons
		a. Pen button - To draw, by default active
		b. Size button - To choose the pen or eraser size
		c. Eraser button - To activate the eraser
		d. Reset button - To clear the canvas
		e. Predict button - To predict the face drawn

    3. Using tkinter for creating a Graphic User Interface

    4. Use Pyscreenshot to capture the canvas as image

    5. Use the trained model('Smiley_Recognition.h5') using the keras load model to predict the face
    	a. The model is trained on the images present in the Dataset directory.
    	b. The type of model used is CNN.

    6. Press the red cross button to close the window

## Important file

Smiley_Recognition.py
Smiley_Recogniton.h5

## Report

The first edition is doing good and predicting with an accuracy of 99%.

## Need Update

The project is only the first edition. I will keep update.
