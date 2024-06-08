# Medicinal Plant Identification Using Convolutional Neural Networks (CNN)

Identification of Different Medicinal Plants/Raw materials through Image Processing Using Machine Learning Algorithms.

Identification is one of the major burning issues in Ayurvedic Pharmaceutics. Several crude drugs are being sold under the same name in the market leading to confusion and their misidentification.

This project aims to develop a system for identifying medicinal plants using Convolutional Neural Networks (CNN). By leveraging the power of deep learning, we can automate the process of plant identification, which is crucial for various applications in healthcare, pharmacology, and botany.

## Dependencies

- [tensorflow]()
- [os]()
- [cv2]()
- [imghdr]()
- [matplotlib]()
- [Numpy]()
- [keras]()

## Language/Framework Used

- [Jupyter Notebook](https://jupyter.org/)

## Preprocessing 

Firstly, the main thing to be done while beginning a image based classification task is to preprocess the images in such a way it becomes easier for computation.
Using CNN model we have classified and extracted the features of the images by importing Conv2D, MaxPooling2D, Dense, Flatten, Dropout.

## Train and Test

The CNN model is trained with the conditions
- epochs=10
- validation_data
- tensorboard_callback

## Loss and Accuracy

- Loss          :     -1.826228469445427e+16
- Accuracy      :      0.023756377398967743
- Val_loss      :      -1.343664949297152e+16
- Val_accuracy  :      0.0262276791036129

## Model Prediction

- Medicinal Plant
- Non Medicinal Plant

## Dataset

Indian Medicinal ⚕️Leaves 🌿 Dataset
(https://www.kaggle.com/datasets/aryashah2k/indian-medicinal-leaves-dataset/data)

