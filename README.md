# Handwritten Digit Classification

## Introduction
This project focuses on training a neural network to classify handwritten digits using the MNIST dataset. The neural network architecture is defined using the Keras library, a high-level neural networks API. The model consists of an input layer, two dense hidden layers with ReLU activation functions, and an output layer with a softmax activation function. The model is then compiled with mean squared error loss and Adam optimizer.

## Features
- Trains a neural network model to classify handwritten digits.
- Utilizes the popular MNIST dataset, consisting of a large collection of labeled images of handwritten digits.
- The model architecture is defined using the Keras library, making it easy to configure and train.
- The neural network consists of an input layer, two dense hidden layers, and an output layer.
- ReLU activation functions are used in the hidden layers, while the output layer employs a softmax activation function.
- The model is compiled with mean squared error loss and optimized using the Adam optimizer.

## Installation
1. Clone this repository: `git clone <repository_url>`
2. Install the required dependencies by running: `pip install -r requirements.txt`
3. Download the MNIST dataset and place it in the designated data folder.
4. Run the main application script: `python digit_classification.py`

## Usage
1. Ensure that the dataset is properly loaded and preprocessed by running the data preprocessing script: `python data_preprocessing.py`.
2. Train the neural network model by executing the training script: `python train_model.py`.
3. Once the model is trained, the main application script can be used to classify handwritten digits: `python digit_classification.py`.

## Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
1. Fork this repository.
2. Create a new branch: `git checkout -b my-new-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request detailing your changes.

## License
This project is licensed under the [MIT License](LICENSE).
