# Dota2 Game Result Prediction

<img src="https://th.bing.com/th/id/OIG.H1LJsc7J07lVh10zF2ho?pid=ImgGn"/>

This repository contains a Python script that uses machine learning to predict the results of Dota2 games.

## Overview

The script uses a neural network model implemented using TensorFlow and Keras. The model is trained on a dataset of Dota2 games, which is split into training, validation, and testing sets. The model's performance is evaluated based on its accuracy on the testing set.


## Code Structure

The code can be divided into several sections:

1. **Data Loading**: The Dota2 Games Results dataset is loaded from Google Drive.

2. **Data Preprocessing**: The data is split into features and target variable, and further split into training, validation, and testing sets. The labels are also converted to one-hot encoded vectors.

3. **Model Definition**: A neural network model is defined with several dense layers and dropout layers for regularization.

4. **Model Training**: The model is trained for 50 epochs using the Adam optimizer and the categorical cross-entropy loss function.

5. **Model Saving and Loading**: The trained model is saved and then loaded again to ensure it has been saved correctly.

6. **Model Evaluation**: The model's performance is evaluated on the testing set, and the test accuracy is printed out.

## Usage

To run the script, you need to have Python installed along with the following libraries:
- pandas
- numpy
- tensorflow
- sklearn
- keras

You also need to have access to the Dota2 Games Results dataset, which should be placed in your Google Drive under the path '/content/drive/MyDrive/colab_test_data/'.

## Contact

If you have any questions or suggestions, feel free to open an issue or submit a pull request.

email : saradhi8142385201@gmail.com

