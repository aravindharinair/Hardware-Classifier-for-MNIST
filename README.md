# Design of an Energy-Efficient Custom Hardware for Classifying Handwritten Digits 

## About
This project deals with the design of an energy-efficient custom hardware that utilizes a quantized convolutional neural network to classify handwritten digits provided in the Modified National Institute of Standards and Technology (MNIST) database.   
Our model was created and trained with Python using the PyTorch library. Once we obtained optimal values from the Python simulation, we translated the model into Verilog RTL. Following this, we designed the hardware on ASU's [ASAP7 7nm PDK](https://asap.asu.edu) using the Innovus APR toolset.


## Guide to the project
The software model can be found in a Python Notebook file since we designed and tested the project on Google Colab.

## Authors
- Ankit Jeevan Berde
- Aravind Hari Nair
- Chiang Wang