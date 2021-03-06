# Regression model using Neural Network
We use the tf-slim library for creating this regression Neural Network model to predict the output-values for any input x.
This model can be applied for all functions of _y=f(x)_ and can be remodelled to any number of features

## Requirements
 * Jupyter Notebook
 * Tensorflow

## Usage

### Prepare Training Dataset 
The train inputs and outputs are persent in ``dtset.txt`` as space-seperated values . Provide the validation dataset in the file ``testset.txt``.Then create a folder called ``ckpt`` for storing the checkpoint.

### Results

The distribution of training dataset is :

![Screenshot](./assets/screenshot1.png "Screenshot 1")

The distribution of validated dataset along with original value and prediction:

> Red indicates ground-truth value blue indicates predicted value

![Screenshot](./assets/screenshot2.png "Screenshot 2")

>>More the training set more accurate the predictions.
