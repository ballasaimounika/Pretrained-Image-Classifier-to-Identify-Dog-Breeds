# 🐾 Pre-trained Image Classifier for Dog Breed Identification   

This repository contains a pre-trained image classifier developed using Python to identify dog breeds. The classifier utilizes three well-known Convolutional Neural Network (CNN) architectures: **AlexNet**, **VGG**, and **ResNet**. Each of these architectures is leveraged to classify images into different dog breeds, as well as determine whether an image contains a dog.

![Dog Image](https://www.pixelstalk.net/wp-content/uploads/images3/Cute_dog_wallpaper_HD.jpg)

---

## 📖 Overview

This project is designed to identify different dog breeds from images and check if an image contains a dog. It includes the following features:

- **🐶 Dog Breed Classifier:** The main part of the project, using pre-trained neural networks to recognize different dog breeds in images. 
- **🔍 Dog Detector:** Checks whether an image contains a dog or not. 
- **🖼️ Image Preprocessing:** Prepares the images by resizing, normalizing, and transforming them so they work well with the CNN models. 
- **📈 Results Analysis:** Measures the performance of the classifier, calculating key metrics such as accuracy, correct matches, and misclassifications.

---

## 🛠️ Getting Started

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/ballasaimounika/Pretrained-Image-Classifier-to-Identify-Dog-Breeds.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd Pretrained-Image-Classifier-to-Identify-Dog-Breeds
   ```

---

## 📝 Instructions

1. **Testing the Classifier:**
   
   - To test the classifier's performance on a set of images, run the following command:
     ```bash
     python test_classifier.py
     ```
     
   - The results will display the accuracy, correct matches, and misclassifications. ✅

2. **Using the Classifier:**
   
   - Save your dog images in the `uploaded_images` folder of the repository. Then, use the provided functions to classify dog breeds in your own Python applications. 📂
     
   - To process the images, run the following command in your terminal:
     ```bash
     sh run_models_batch_uploaded.sh
     ```
     
   - Once the script runs, you can view the results in the following text files:
     
     - **resnet_uploaded-images.txt** - contains the results using the ResNet CNN model. 📄
     - **alexnet_uploaded-images.txt** - contains the results using the AlexNet CNN model. 📄
     - **vgg_uploaded-images.txt** - contains the results using the VGG CNN model. 📄
       
   - Run the main class file, `check_images.py`, with the following command:
     ```bash
     python check_images.py
     ```
     
   - Then, compare the results to those produced by your program when you ran `run_models_batch_uploaded.sh`.

---

## 🖥️ CNN Architectures

### 🐕 AlexNet

AlexNet is a deep CNN architecture designed for image recognition tasks. It consists of five convolutional layers followed by three fully connected layers. 

To use AlexNet with the classifier, use the command:
```bash
--arch alexnet
```

### 🐩 VGG

VGG (Visual Geometry Group) is a CNN architecture known for its simplicity and depth, using 3x3 convolutional layers throughout the architecture. It is particularly effective for image classification tasks due to its uniform architecture and depth.

To use VGG with the classifier, use the command:
```bash
--arch vgg
```

### 🐕‍🦺 ResNet

ResNet (Residual Neural Network) is a CNN architecture designed to address the vanishing gradient problem in deep networks. It introduces residual connections, allowing gradients to flow through the network more effectively during training. This architecture enables the construction of very deep networks without the degradation of performance.

To use ResNet with the classifier, use the command:
```bash
--arch resnet
```

---

## 🤝 Welcome to contribute

Here’s how you can help:

- **Report Bugs or Suggestions:** If you encounter a bug or have a suggestion, please open an issue to let me know.
- **Enhance the Project:** If you’d like to improve the project, feel free to submit a pull request with a clear explanation of your changes.

Thank you for your interest in contributing!
