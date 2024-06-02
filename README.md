MNIST Classification with TensorFlow and Keras
=====================================================

This repository contains a simple MNIST classification model using TensorFlow and Keras.

Getting Started
---------------

### Prerequisites

* Python 3.6+
* TensorFlow 2.3+
* Keras 2.3+

### Installation

1. Clone the repository: `git clone https://github.com/your-username/mnist-classification.git`
2. Install the required packages: `pip install -r requirements.txt`

### Running the Code

1. Run the code: `python mnist_classification.py`

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
