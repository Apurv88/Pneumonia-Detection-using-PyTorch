# Pneumonia-Detection-using-PyTorch
This project implements and compares several deep learning models to classify chest X-ray images as either Normal or Pneumonia.
Pneumonia Detection serves as an ablation study to compare the performance of a custom-built Convolutional Neural Network (CNN) against popular pre-trained models (ResNet50, VGG16, and MobileNetV2) using transfer learning.

Models Compared
Baseline CNN: A custom-built, simple CNN with 3 convolutional blocks and a fully connected head.
<img width="594" height="366" alt="image" src="https://github.com/user-attachments/assets/9b968e93-d4e5-4783-8ea0-e29c3759fd69" />

ResNet50: A pre-trained ResNet50 model with its final layer replaced for binary classification.
<img width="591" height="349" alt="image" src="https://github.com/user-attachments/assets/d75ac0a9-e46f-4693-89d3-39316e035f8c" />

VGG16: A pre-trained VGG16 model with its final classifier replaced.
<img width="544" height="306" alt="image" src="https://github.com/user-attachments/assets/41b14a89-240e-4832-8909-f2739d9bc44c" />

MobileNetV2: A pre-trained MobileNetV2 model with its final classifier replaced.
<img width="542" height="304" alt="image" src="https://github.com/user-attachments/assets/b3f04c63-472b-4e3d-8bfe-1433c4ca2e05" />

Dataset:
This project uses the "Chest X-Ray Images (Pneumonia)" dataset from Kaggle.
Link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
The script uses the kagglehub library to automatically download and unzip the dataset into the correct directory.
