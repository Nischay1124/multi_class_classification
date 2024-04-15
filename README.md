# multi_class_classification
This project is a demonstration of image classification using Convolutional Neural Networks (CNNs) implemented with TensorFlow and Keras. The goal is to classify images of various objects into different categories.

Dataset
The dataset consists of images of the following objects:

Clock
Angel
Apple
Arm
Baseball bat
Baseball
Bed
Book
Cake
Face
The images are preprocessed and normalized before being used for training the model.

Model Architecture
The CNN model architecture includes:

Three Convolutional layers with ReLU activation
MaxPooling layers to downsample the spatial dimensions
Dense layers for classification
Softmax activation for multiclass classification
Training
The model is trained using the Adam optimizer and categorical crossentropy loss. The training data is split into training and testing sets, and the model is trained for 10 epochs.

Evaluation
The model's performance is evaluated on the testing set, and metrics such as accuracy are used to measure its performance.

Results
The model achieves an accuracy of 95% on the testing set, demonstrating its effectiveness in classifying the images.
