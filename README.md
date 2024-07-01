# Brain-Tumor-MRI-Classification-with-CNNs 🧠🧠

The Brain Tumor MRI Classifications with CNNs project aims to classify brain tumors using Convolutional Neural Networks (CNNs). 🧠 The script utilizes the Keras Tuner library to perform hyperparameter tuning on a CNN model, optimizing it for the highest validation accuracy. It begins by importing necessary libraries and defining the image size and batch size for the dataset. To address potential GPU memory issues, it disables the GPU and configures memory growth. The script sets up data augmentation and preprocessing using the `ImageDataGenerator` class, which performs various image transformations like rotation, shifting, shearing, and flipping to enhance the training dataset. The dataset is divided into training and validation subsets from the specified directory. The `build_model` function constructs a sequential CNN model with configurable layers, which is then tuned using Keras Tuner's `RandomSearch` to find the best combination of hyperparameters. The hyperparameter search involves trying different configurations of convolutional and dense layers. Finally, the best model configuration is obtained and summarized. This project efficiently leverages machine learning techniques to classify brain tumors, making it a valuable tool for medical image analysis and diagnostics.


The 'MRI Trials' Image:

The output image shows that the neural network was trained and tuned to classify brain tumors from MRI images with a high accuracy of about 89%. It also provides a detailed look at the structure of the best-performing model, including the types of layers used and the number of parameters. This information helps in understanding how the model processes the images and makes its predictions.

The 'MRI Graph': 

These graphs and the accuracy score provide insight into how well the model is performing in terms of both training and validation. The high validation accuracy (91.26%) indicates that the model is performing well in classifying brain tumors from MRI images. The model is saved for future use, ensuring that the best version of the model can be utilized without retraining.

The 'Pituitary Tumor' photo is an example of images uploaded into the script for training and testing purposes. 





