# Sign Language Detection Project

This project is about building a deep learning model for sign language detection. The model is trained on a dataset of images representing different sign language gestures.

# Software Specifictaions

1. Python: The code is written in Python. You will need a Python environment to run the code. You can use an environment like Anaconda or simply install Python on your machine.
2. Keras: This is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation.
3. TensorFlow: This is an open-source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.
4. NumPy: This is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
5. OS: This is a module in Python that provides functions for interacting with the operating system. OS comes under Python’s standard utility modules.
6. TensorBoard: This is a tool for providing the measurements and visualizations needed during the machine learning workflow. It enables tracking experiment metrics like loss and accuracy, visualizing the model graph, projecting embeddings to a lower dimensional space, and much more.

# Instructions

1. Clone the Dataset: The first step is to clone the dataset from the GitHub repository using the command !git clone https://github.com/kumarvivek9088/aslsigndataset.git.
2. Import Necessary Libraries: Import the necessary Keras and other libraries.
3. Data Preprocessing: Use ImageDataGenerator to preprocess the images. This includes rescaling the images and splitting the dataset into training and validation sets.
4. Model Building: Build a Sequential model with multiple Convolutional layers, MaxPooling layers, Dropout layers, and Dense layers. The model uses ‘relu’ activation function for the hidden layers and ‘softmax’ for the output layer.
5. Compile the Model: Compile the model using ‘adam’ optimizer, ‘categorical_crossentropy’ as the loss function, and ‘accuracy’ as the metric.
6. Train the Model: Train the model using the fit method. The training data is the train_generator, and the validation data is the validation_generator. The model is trained for 100 epochs.
7. TensorBoard: Use TensorBoard for visualizing the training process. The logs are stored in the “Logs” directory.
8. Save the Model: Finally, save the model in JSON format and the weights in H5 format.
