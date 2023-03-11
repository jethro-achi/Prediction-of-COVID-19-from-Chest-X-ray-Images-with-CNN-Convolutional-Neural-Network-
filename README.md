Prediction of COVID-19 from Chest X-ray Images with CNN (Convolutional Neural Network)
In this project, Built and trained a convolutional neural network in Keras with TensorFlow as backend from scratch to predict patients if they were infected with COVID-19 or not using their chest X-ray images. Matplotlib was used for data visualization. Data preprocessing and data augmentation was carried out using tensorflow 2.0 The model used was sequential with a combination of convolutional layers, pooling layers, dropout layers, dense layers with relu activation and output layer with sigmoid activation. The dataset contained the lungs X-ray images of both groups i.e non-covid and covid infected patients. The dataset was obtained from kaggle. Metrics chosen for model evaluation were Training set, test set and validation set accuracy. Adam optimizer with learning rate of 0.001 was choosed for gradient descent The entire project was carried out on the Google Colab environment Results of the model were following:

Training Set Accuracy : 98.41 %

Training Set Loss : 0.0490

Validation Set Accuracy : 97.51 %

Validation Set Loss: 0.0759

Test Set Accuracy : 94.83 %

Test Set Loss : 0.1141

Install Necessary Modules:
Open your Anaconda Prompt propmt and type and run the following command (individually):
  pip install pandas
  pip install numpy  
  pip install tensorflow
Once Installed now we can import it inside our python code.

Frequently asked questions ❔
How can I thank you for writing and sharing this tutorial? 🌷
You can Star Badge and Fork Badge Starring and Forking is free for you, but it tells me and other people that it was helpful and you like this tutorial.

Go here if you aren't here already and click ➞ ✰ Star and ⵖ Fork button in the top right corner. You'll be asked to create a GitHub account if you don't already have one.

How can I read this tutorial without an Internet connection? GIF
Go here and click the big green ➞ Code button in the top right of the page, then click ➞ Download ZIP.

Download ZIP

Extract the ZIP and open it. Unfortunately I don't have any more specific instructions because how exactly this is done depends on which operating system you run.

Launch ipython notebook from the folder which contains the notebooks. Open each one of them

Kernel > Restart & Clear Output

This will clear all the outputs and now you can understand each statement and learn interactively.

If you have git and you know how to use it, you can also clone the repository instead of downloading a zip and extracting it. An advantage with doing it this way is that you don't need to download the whole tutorial again to get the latest version of it, all you need to do is to pull with git and run ipython notebook again.


Licence 📜
You may use this tutorial freely at your own risk. See LICENSE.

Copyright (c) 2020 Jethro Achelam
