# Traffic

## Introduction

Traffic is a project aimed at classifying traffic signs in real time using input from a laptop's front camera. A key feature of this project is the custom dataset created for training the model, consisting of various traffic signs. This project leverages OpenCV and TensorFlow Lite to achieve real-time traffic sign classification.

## Results

The primary outcome of this project is the successful creation and use of a custom dataset for traffic sign classification. Initially, a small dataset of 17 images was created and labeled using LabelImg, which resulted in a model that could classify traffic signs but also produced a significant number of false positives. 

After expanding the dataset to over 100 images with diverse backgrounds, lighting conditions, and angles, and increasing the model training steps to 30,000, the accuracy of the model improved significantly, reducing the false positives. 

Notable insights from this project include:
- Custom datasets can be effectively created and used for specific image classification tasks.
- Increasing the diversity of training data and the number of training iterations can significantly enhance model performance.
- Understanding and utilizing tools like OpenCV and TensorFlow Lite are crucial for real-time image processing tasks.

![image](https://github.com/AlokChedambath64/traffic-/assets/110228030/0a24729d-f135-42ce-a58c-acc3b89d24da)


![Screenshot 2024-05-10 211404](https://github.com/AlokChedambath64/traffic-/assets/110228030/bdd4c2d7-a7e6-4cc2-a792-bdd22f3ad9b4)



## My Process

1. **Learning OpenCV**: Started by learning how OpenCV works and how to access the laptop's front camera.
2. **Exploring TensorFlow Lite**: Gained knowledge about TensorFlow Lite models for lightweight, real-time applications.
3. **Creating a Dataset**: Made an initial dataset of 17 images with 5 different traffic signs and labeled them using LabelImg.
4. **Initial Model Training**: Trained a model with the initial dataset, achieving some correct classifications but many false positives.
5. **Improving the Dataset**: Expanded the dataset to over 100 images, ensuring diversity in backgrounds, lighting, and angles.
6. **Enhanced Training**: Increased the number of training iterations to 30,000, which significantly reduced false positives and improved accuracy.

### Tools and Libraries
- **OpenCV**: For real-time image capture and processing.
- **Python**: Programming language used for the project.
- **TensorFlow**: Machine learning framework used to train the models.
- **LabelImg**: Tool for labeling images in the dataset.

## Setting Up

### Prerequisites
- Python 3.x
- OpenCV
- TensorFlow
- LabelImg (for dataset creation and labeling)

