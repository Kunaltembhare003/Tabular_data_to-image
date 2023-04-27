# Tabular Data to Image Conversion for Pattern Recognition using CNN

This project aims to convert tabular data into images and apply Convolutional Neural Network (CNN) techniques for pattern recognition. The goal is to leverage the power of CNNs, traditionally used for image analysis, to identify patterns and relationships within tabular data.

## Table of Contents
[comment]: <> (This is a comment, it will not be included)
[comment]: <> (in  the output file unless you use it in)
[comment]: <> (a reference style link.)

- [Project Description](#project-description)
[comment]: <> (- [Installation](#installation))
- [Usage](#usage))
- [Data](#data)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)


## Project Description

In this project, we explore a approach to analyze tabular data using CNNs. Instead of treating the data as traditional tabular input, we convert it into images, where each cell value or feature becomes a pixel in the image. By visualizing the data in this way, we can potentially uncover patterns, correlations, and trends that may be harder to detect in the original tabular format.

## Usage

1. Prepare your tabular data in CSV format.
1. Run the preprocessing scripts to convert the tabular data into images suitable for CNN analysis.
1. Train the CNN model using the generated images.
1. Evaluate the model's performance on test data.
1. Explore the results and interpret the patterns discovered by the model.

## Data

The tabular data used in this project should be in CSV format. Each row represents a sample or instance, and each column represents a feature or attribute. The dataset should have a target variable (labels) indicating the class or category of each sample.

## Model Architecture
The CNN model architecture consists of several layers designed to extract features from the input images and classify them into different classes. The model architecture may vary based on the specific requirements of your project. Refer to the code documentation for details on the model architecture implemented in this project. <br>
![Alt text](https://github.com/Kunaltembhare003/Tabular_data_to-image/blob/main/image/CNN_tabular_data_to_image.jpg)

## Training

During the training phase, the model learns to recognize patterns and relationships in the tabular data converted into images. The training process involves feeding the model with labeled images and adjusting its parameters to minimize the loss function. Training hyperparameters, such as the learning rate, batch size, and number of epochs, can be customized according to your dataset and requirements.

## Evaluation

The trained CNN model is evaluated on test data to assess its performance. Evaluation metrics such as accuracy, precision, recall, and F1-score are used to measure the model's effectiveness in pattern recognition and classification tasks. These metrics provide insights into the model's ability to identify patterns and make accurate predictions.

## Results

The project's results include visualizations, tables, and performance metrics that showcase the patterns and relationships discovered by the CNN model. These results help in understanding the effectiveness of the approach and provide insights into the original tabular data. 74% of accuracy has been achived but model is not geralized well and shows overfitting.
### Train and validation set
![alt text](https://github.com/Kunaltembhare003/Tabular_data_to-image/blob/main/image/CNN_modle_result.png)
### Test set
| precision    | recall | f1-score | support |    |
|--------------|--------|----------|---------|----|
| 0            | 0.73   | 0.97     | 0.83    | 33 |
| 1            | 0.50   | 0.08     | 0.13    | 13 |
| accuracy     |        |          | 0.72    | 46 |
| macro avg    | 0.61   | 0.52     | 0.48    | 46 |
| weighted avg | 0.66   | 0.72     | 0.63    | 46 |

## Contributing
Contributions to this project are welcome. If you have suggestions for improvements, encounter any issues, or want to contribute new features, please follow the standard GitHub workflow (fork, branch, pull request) to submit your contributions.

