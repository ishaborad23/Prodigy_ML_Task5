# Prodigy_ML_Task5

Food Calorie Estimation:
This project aims to develop a machine learning model that accurately recognizes food items from images and estimates their calorie content. The model is designed to help users track their dietary intake and make informed food choices.

Overview:
This project focuses on using a convolutional neural network (CNN) to identify various food items from images and estimate their calorie content. Accurate calorie estimation from food images is a crucial aspect of dietary management and health monitoring.

Dataset : https://www.kaggle.com/datasets/imbikramsaha/food11
The dataset used for training and testing the model is the Food11 dataset from Kaggle. It contains labeled images of various food items across different categories. The dataset contains 11 categories of food images divided into training and testing classes

Data Preprocessing
Image Resizing: Resizing images to a consistent size suitable for the VGG16 model.
Normalization: Scaling pixel values to the range [0, 1].
Data Augmentation: Applying techniques like rotation, zoom, and horizontal flipping to enhance the dataset's diversity.
Model Architecture
The model is built using the VGG16 architecture, a pre-trained deep learning model known for its strong performance in image classification tasks. The VGG16 network has been fine-tuned to recognize food items and estimate their calorie content.

Base Model: VGG16 (pre-trained on ImageNet)
Custom Layers: Added dense layers for calorie estimation
Activation Functions: ReLU and softmax
Evaluation
The model's performance was evaluated using the following metrics:

Accuracy: Classification accuracy for food recognition.
Confusion Matrix: Visual representation of the classification results.
Conclusion
The VGG16-based model demonstrates strong potential in accurately recognizing food items and estimating their calorie content. This model can be an effective tool for dietary tracking and health management.
