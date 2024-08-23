# TransferLearning_with_pre_trained_resNet18
**Author: [Haseeb Ul Hassan]**
# Ants and Bees Classification using Transfer Learning

## Project Overview
<br>
This repository contains the code and resources for training a convolutional neural network (CNN) to classify images of ants and bees. Transfer learning is utilized to leverage pre-trained models, enabling faster training and improved accuracy.

## Dataset

The dataset is organized into two main folders: train and val.
<br>
Training set (train): Contains images used to train the model.
Validation set (val): Contains images used to evaluate the model's performance during training.

Each of these folders has subfolders for the two classes, ants and bees.
## Model Architecture

The project uses a pre-trained model (ResNet) for transfer learning. The final layers are replaced to adapt the model to the binary classification task (ants vs. bees).
<
### Key steps:
Feature Extraction: The pre-trained model is used to extract features from the images.
Classification: The final fully connected layers are fine-tuned to classify the images into ants or bees.


To get started, clone the repository and install the necessary dependencies:




## Results
The trained model achieved an accuracy of (given in notebook) on the validation set. Detailed results, including confusion matrices and loss curves, can be found in the notebook.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any improvements or suggestions.


