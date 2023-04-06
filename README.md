# Audio Classification
This repository contains a Jupyter notebook audio-classification.ipynb that demonstrates an audio classification model using Mel-Frequency Cepstral Coefficients (MFCCs) as features and a neural network for classification. The model is trained on the UrbanSound8K dataset.

## Prerequisites
To run this notebook, you need to have the following libraries installed:

numpy

pandas

matplotlib

librosa

IPython

tqdm

tensorflow

sklearn

## Usage

You can clone this repository and run the audio-classification.ipynb notebook in Jupyter or any other compatible environment.

The notebook includes the following steps:

Load and visualize an audio file from the dataset.

Load the metadata file that contains the class labels.

Extract features from the audio files using MFCCs.

Split the data into training and testing sets.

Build a neural network model using TensorFlow and Keras.

Train the model on the training data and evaluate its performance on the testing data.

The final accuracy of the model on the testing data is 0.9049.

## Credits
This project was created with the guidance of Krish Naik through his tutorial on YouTube. The dataset used in this project is the UrbanSound8K dataset.

## License
The code in this repository is released under the MIT License. The UrbanSound8K dataset has its own license, which can be found at https://urbansounddataset.weebly.com/urbansound8k.html.
