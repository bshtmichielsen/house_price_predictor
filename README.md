# House Price Predictor
This repository provides a foundational notebook designed to introduce students to machine learning using PyTorch Lightning. The example focuses on a regression problem, utilizing the Boston House Price dataset, which is presented in a CSV format and contains 13 features that are instrumental in predicting the selling price of a house. To maintain clarity and facilitate understanding for those new to machine learning, the model architecture consists of a single fully connected layer. While I acknowledge that employing a neural network for such a straightforward regression task may not be the most practical approach in real-world scenarios, the primary goal of this exercise is to familiarize students with the PyTorch Lightning framework. This example serves as a stepping stone, allowing students to grasp the fundamental concepts of machine learning while encouraging exploration and experimentation. 

![house-price-predictor](house-price-predictor.avif)

As you go through the notebook, I invite you to think critically about its design and consider potential enhancements, thereby deepening your understanding of regression techniques, the PyTorch Lightning library and machine learning in general.

## Learning alignments
The following aspects of machine learning are part of this example:
 - Pytorch Lightning project structure (DataSet, DataModule, LightningModule, Trainer)
 - Working with data files, in this case CSV
 - Neural Network building using layers.
 - Validation (using a val dataset during training)
 - Evaluation (using a test dataset after training)

## Possible consideration for improvement
This notebook is an example on how to get started, it is open for improvements and enhancements. Feel free to clone my work and use it to study and learn. Things to consider if you want to improve this work:

- Maybe adding an additional (fully) connected layer makes the model better?
- Perhaps a visualization of the errors at the end would be interesting.
- Try with your own CSV file!

## Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!

Michielsen, Bas S.H.T. (2025) "House Price Predictor" GitHub: https://github.com/bshtmichielsen/house_price_predictor