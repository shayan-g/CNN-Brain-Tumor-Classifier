# CNN-Brain-Tumor-Classifier
This project is a convolutional neural network (CNN) built with Keras for binary classification of brain MRI images—tumor vs no tumor. The model architecture and training process are inspired by a publicly available Kaggle notebook, adapted and simplified for educational and experimental purposes.

# Data

The repository includes a `.zip` file containing the MRI images, organized as follows:

brain_tumor_dataset/
- **yes/**: images with tumors  
- **no/**: images without tumors  

Unzip the archive and point your `image_dir` to the `brain_tumor_dataset` folder before running the code.

# Model Overview
Framework: TensorFlow / Keras

Input shape: (128, 128, 3)

Architecture: Convolutional layers → BatchNorm → MaxPooling → Dense

Activation: ReLU and softmax

Loss function: categorical_crossentropy
