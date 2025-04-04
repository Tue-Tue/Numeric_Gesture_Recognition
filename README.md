# Numeric_Gesture_Recognition
## Members:
- Đinh Tuệ Đức
- Trần Quang Đạt
- Nguyễn Thị Ngọc Trâm
## Introduction:
This project focuses on recognizing digits in hand signs to assist hearing-impaired individuals in daily communication. It serves as a foundation for more complex research and applications, such as translating sign language into sentences or paragraphs.
## Problem Statement:
- Input: Images of hand signs representing numbers from 0 to 9 in ASL (American Sign Language). The images may come in different formats such as JPEG, PNG, and may vary in size.
- Output: Predicted label corresponding to the hand sign digit.
- Constraints: The input images need to be preprocessed to normalize their dimensions, remove noise, and prepare them for classification.
## Feature Extraction:
The project utilizes the following feature extraction methods:
- Histogram of Oriented Gradients (HOG): Extracts local features based on pixel gradient orientations.
- Sobel: Extracts edge features by computing the gradient magnitude in horizontal and vertical directions.
## Classification Models:
We experimented with three machine learning models for classification:
- Support Vector Machines (SVM): Finds an optimal boundary between classes.
- k-Nearest Neighbors (KNN): Classifies based on the k-nearest neighbors.
- LogisticRegression: Estimates class probabilities and assigns the label with the highest likelihood.
## Experiments:
### Dataset:
- Dataset used: American Sign Language Dataset
- Image size: 128x128
- Color Space: RGB
- Number of Classes: 10 (Digits 0-9)
### Model evaluation:
- k-NN + HOG with correlation, k = 17
- LogisticRegression + HOG, c = 7
![image](https://github.com/user-attachments/assets/20d9369d-c00b-4e26-a2c5-165b2b0904a0)
## Demo:
![image](https://github.com/user-attachments/assets/efe2e86d-0d8a-4386-a9a5-c96e5af6ae6a)
## References:
- https://www.kaggle.com/datasets/ayuraj/asl-dataset
- https://machinelearningcoban.com/2017/02/17/softmax/
- https://viblo.asia/p/part1-edge-detection-voi-opencv-L4x5xLVB5BM
- https://phamdinhkhanh.github.io/2019/11/22/HOG.html

