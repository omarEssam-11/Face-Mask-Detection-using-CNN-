# Face Mask Detection
The project aims to develop a real-time face mask detection system using 
Convolutional Neural Networks. This project will ensure compliance with mask
wearing in public spaces and  classify them into two 
categories: "with mask" and "without mask." contributing to public health safety. 

## Overview
- Features
  - Mask detection from images.
  - Classification of faces as Masked or Unmasked.
- Expected Outcomes
  - A functional and accurate detection system.
  - High performance in terms of speed and accuracy.

### Our pipeline consists of two steps:
  1. We make a mask/no_mask prediction for each of them
  2. We return an annotated image with the predictions

## Team Collaboration 
- Collaboration 
  - We worked together closely, ensuring smooth communication and 
mutual support throughout the development process.
- Team Meeting 
  - meeting one: We proposed the project idea and conducted a comprehensive study on 
the requirements needed for the project.
  - meeting two: We collected the appropriate dataset to start the project and divided the 
tasks, including coding and optimization. 
  - meeting three: We implemented the necessary algorithms for the project and trained 
the model on different datasets so that it can classify new datasets as we intend.
  - meeting four: We We had a Zoom meeting before the discussion to review the entire project.

### Technical Methodology 
- Tools and Technologies
  - Python, TensorFlow, OpenCV, and numpy, sklearn. 
  - Tensorflow / Keras
  - Kaggel Notebook



# Steps For Building Project
### Collecting Data and Datasets
- collecting data from real-world images and supplemented it with datasets sourced from *Kaggle: [link 1](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset),[link 2](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset), ensuring a diverse and comprehensive dataset.We used two datasets and combined them together .Datasets consisting of **more than 19,000 RGB images, which include individuals **wearing masks* and others *without masks*.This dataset provides a solid foundation for training and evaluating our face mask detection model.

### Data preprocessing
- *Resize Images*: 128x128
- *Support Format (JPG, PNG,JPEG)*
- *Convert Image To RGB*
- *Label Images*: mask = 1, unmask = 0
- *Convert Images to Numpy Array*
- *Normalize Data*: Dividing by 255
- *Shuffel Data*

### Building Model
- *Train Test Split*:  70% for training, 20% for testing , 10% for validation
- *Model Architecture: We employed a **Convolutional Neural Network (CNN)* architecture, which optimized for binary classification.

<img src="https://github.com/omarEssam-11/Face-Mask-Detection-using-CNN-/blob/main/src/arch.png" width="600px">

### Evaluation
- *Accuracy*
  
<img src="https://github.com/omarEssam-11/Face-Mask-Detection-using-CNN-/blob/main/src/Screenshot%202024-12-26%20004055.png">

- *Classification Report*

<img src="https://github.com/omarEssam-11/Face-Mask-Detection-using-CNN-/blob/main/src/Screenshot%202024-12-26%20003309.png">

- *Confusion Matrix*

<img src="https://github.com/omarEssam-11/Face-Mask-Detection-using-CNN-/blob/main/src/conmatrix.png">
