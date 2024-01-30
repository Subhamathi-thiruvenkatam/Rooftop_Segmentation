# Rooftop_Segmentation using U-Net Model

This is the final year project of my undergraduate studies, focusing on the application of deep learning techniques for semantic segmentation of aerial images. In this project, the AIRS dataset is utilized, comprising satellite images and corresponding segmented masks for roof structures. The code represents the implementation of a U-Net model for semantic segmentation of aerial images using the AIRS dataset. Here's the code breakdown:


Dataset Overview
Training Set: 178 aerial satellite images along with segmented masks.
Validation Set: 11 aerial images and their corresponding segmented masks.
Testing Set: 18 aerial images and their segmented masks.

Model Architecture
Implemented a U-Net model for semantic segmentation. The model is designed to identify and outline rooftop structures in the given images. The architecture includes convolutional and pooling layers for feature extraction, followed by deconvolutional layers for precise segmentation.

Data Preprocessing
Trained the U-Net model on the training set (178 images) and validated on the validation set (11 images).
Used metrics such as Intersection over Union (IOU), Dice Coefficient, and Matthews Correlation Coefficient (MCC) to evaluate the model's performance.

Results and Visualization
The model demonstrates promising results in segmenting buildings. The evaluation metrics provide insights into the accuracy and efficiency of the segmentation process. Additionally, a function is provided to draw bounding boxes and fill identified buildings on the segmented masks, enhancing the visual interpretation of the model's performance.

