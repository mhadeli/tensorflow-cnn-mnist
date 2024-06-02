MNIST Classification with TensorFlow and Keras
=====================================================


This repository contains a TensorFlow and Keras implementation of a convolutional neural network (CNN) for image classification on the MNIST dataset. The code is written in Python (Jupyter notebook) and uses the TensorFlow and Keras libraries to build and train the model.


Getting Started
---------------

### Prerequisites

* Python 3.6+
* TensorFlow 2.3+
* Keras 2.3+

## Code Structure

The code is organized into the following files:

* `CNNs-improved.ipynb`: The main Python script that loads the MNIST dataset, builds and trains the CNN model, and evaluates its performance.
* * `cnns-mnist-digit-recognition.ipynb`: This notebook is the the base note book and I used it from [Kaggle](https://www.kaggle.com/code/muhammadibrahimqasmi/unveiling-cnns-for-mnist-digit-recognition).
* `README.md`: This file, which provides an overview of the project and its requirements.


### Model Architecture

The model architecture consists of the following layers:

* Conv2D (32 filters, kernel size 3x3, activation='relu')
* MaxPooling2D (pool size 2x2)
* Conv2D (64 filters, kernel size 3x3, activation='relu')
* MaxPooling2D (pool size 2x2)
* Conv2D (64 filters, kernel size 3x3, activation='relu')
* Flatten
* Dense (64 units, activation='relu')
* Dense (10 units, activation='softmax')

### Training

The model is trained using the Adam optimizer and sparse categorical cross-entropy loss. The training data is split into training and validation sets (80% and 20%, respectively).

### Evaluation

The model is evaluated using the test data, and the test loss and accuracy are printed to the console.

### Model Saving

The trained model is saved to a file named `model.h5`.

### Plotting

The training and validation accuracy and loss are plotted using Matplotlib.

License
-------

This project is licensed under the MIT License.

Acknowledgments
---------------

This project was inspired by the TensorFlow and Keras documentation.

Contributing
------------

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

Contact
-------

If you have any questions or issues, please don't hesitate to contact me at [datamind@outlook.de](mailto:datamind@outlook.de).
