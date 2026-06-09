# Neural-Network---FashionMNIST-dataset
This project implements a Multilayer Perceptron (MLP) using PyTorch to classify clothing items from the Fashion MNIST dataset.

## Dataset
The project uses the Fashion MNIST dataset available through torchvision.datasets.FashionMNIST.

## Project Objectives
Load and preprocess the Fashion MNIST dataset.

Create training and test datasets using PyTorch DataLoaders.

Implement an MLP classifier using PyTorch.

Train and evaluate the model.

Tune a selected hyperparameter.

Generate and analyse a confusion matrix.

Calculate accuracy, precision, recall, and F1-score

## Model Architecture
The MLP consists of:

Input Layer: 784 neurons (28 × 28 flattened image)

Hidden Layer: Tuned during experimentation

ReLU Activation Function

Output Layer: 10 neurons (one for each clothing category)

## Performance Metrics
Accuracy	85.29%

Precision (Macro)	85.45%

Recall (Macro)  85.14%

F1 Score (Macro)	85.16%

## Technologies Used
Python

PyTorch

NumPy

Scikit-learn

Jupyter Notebook

## Running the Project
### Clone the repository:
git clone <repository-url>

cd <repository-name>
### Install dependencies:
pip install torch torchvision numpy scikit-learn jupyter
### Launch Jupyter Notebook:
jupyter notebook
### Open and run:
fashion_mnist_task.ipynb

## Author
Stephanie Bergh
