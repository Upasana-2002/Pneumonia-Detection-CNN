## Pneumonia Detection from Chest X-rays
This project focuses on building a deep learning model that can automatically detect pneumonia from chest X-ray images. Pneumonia is a serious lung infection, and radiologists usually examine chest X-rays to identify it. The idea of this project was to see how well a machine learning model can help in this task.

 ## Project Objectives

. To classify chest X-ray images into Normal and Pneumonia cases.
. To apply image preprocessing and understand how it improves model accuracy.
. To implement a Convolutional Neural Network (CNN) from scratch.
. To evaluate model performance and visualize the results.

 ## Tools & Libraries

. Programming Language: Python
. Deep Learning Framework: TensorFlow, Keras
. Data Handling: NumPy, Pandas
. Visualization: Matplotlib, Seaborn
. Image Processing: OpenCV

## Approach

## 1. Dataset
. Used chest X-ray dataset containing images of Normal and Pneumonia cases.
. Split data into training, validation, and test sets.

## 2. Preprocessing
. Resized all images to the same dimension.
. Normalized pixel values (0–255 → 0–1).

## 3. Applied data augmentation (rotation, zoom, horizontal flip) to reduce overfitting.
. Model Architecture
. Built a CNN with convolution, pooling, dropout, and dense layers.
. Trained using Adam optimizer and binary crossentropy loss.
. Evaluation

## Results

. Achieved around 90% test accuracy.
. Model is able to correctly identify most pneumonia cases.

Example:
 . Normal X-ray → Predicted Normal (97% confidence)
 . Pneumonia X-ray → Predicted Pneumonia (89% confidence)

## Future Work

. Experiment with transfer learning models (VGG16, ResNet50) to improve accuracy.
. Extend classification to Bacterial vs Viral Pneumonia.
. Deploy the model as a web application where users can upload X-rays.
. Monitored accuracy and loss curves during training.

Evaluated on test data and visualized a confusion matrix.

Tested model predictions on sample chest X-ray images.
