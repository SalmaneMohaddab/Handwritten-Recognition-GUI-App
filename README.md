# Handwritten-Recognition-GUI-App

## Introduction
This project focuses on the recognition of handwritten digits using the MNIST dataset. It implements a Convolutional Neural Network (CNN) with Python, TensorFlow, and Keras to classify and predict handwritten digits.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Information](#model-information)
- [GUI Application](#gui-application)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Installation
### Prerequisites
- Python 3.8+
- TensorFlow 2.x
- Keras

### Setup
```bash
git clone https://github.com/salmane34/Handwritten-Recognition-GUI-App.git
cd Handwritten-Recognition-GUI-App
pip install -r requirements.txt
```

### Usage

 First of all you need to generate the model that you are going to use in the application , you can use jupyter to run the execution step by step , after running the whole main.ipynb Notebook , a new file called model.h5 will be generated .
 Now you can run the next Notebook (DigitGui.ipynb) using jupyter again and your Desktop application will run successfully 😉.

## Dataset

The MNIST was developed by Yann LeCun, Corinna Cortes, and Christopher Burges to evaluate machine learning models on the problem of classifying handwritten digits. It was compiled from many different sources available from the National Institute of Standards and Technology (NIST), including images of handwritten digits from U.S. census forms and credit card application forms. The images were normalized and centered to facilitate analysis by machine learning models.

Each image is a 28 x 28 pixel square (784 pixels in total). A standard pin of the dataset is used to evaluate and compare models, where 60,000 images are used to train a model and a separate set of 10,000 images are used for testing.

### Model Information

We can use a model based on a Convolutional Neural Network (CNN) to solve the problem of recognizing handwritten digits on the MNIST dataset, which can be represented as follows:

![Example Image](https://tensorflownet.readthedocs.io/en/latest/_images/cnn.png)

## GUI Application

The GUI application for the handwritten digit recognition project provides an intuitive interface where users can draw digits on a canvas using their mouse or a stylus. Once a digit is drawn, users can click the 'Predict' button, prompting the application to process the input and use a pre-trained neural network model to predict and display the corresponding digit. The interface also features a 'Clear' button, allowing for easy resetting of the canvas for new inputs.


![Example Image](https://github.com/salmane34/Handwritten-Recognition-GUI-App/blob/668106ee6dd438e2994312c7236426b212ba7c3f/Images/1.png)

## Results

![Example Image](https://github.com/salmane34/Handwritten-Recognition-GUI-App/blob/668106ee6dd438e2994312c7236426b212ba7c3f/Images/2.png)


## Contributing

Contributions are welcome! If you have a suggestion that would make this better, please fork the repo and create a pull request. 

Don't forget to give the project a star! Thanks again!

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Salmane Mohaddab - salmanemohaddab@gmail.com

Project Link: [ https://github.com/salmane34/ALGO-Compiler.git ]
