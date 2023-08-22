## Alpacas Detection using YOLOv8 🦙🔍
### Background:
This project aims to detect and localize alpacas in images using YOLOv8, a state-of-the-art object detection algorithm. I trained the model for alpacas detection using a small dataset and limited training resources, achieving promising results.

### Dataset 🗂 :
Our dataset consists of a small number of images containing alpacas. While a larger and more diverse dataset would be ideal, we aimed to demonstrate the feasibility of training a YOLOv8 model even with limited data. The dataset is divided into training and validation sets to facilitate training and evaluation.
Due to the limited size of the dataset, augmentation techniques such as flipping, rotation, and scaling were applied to artificially increase the diversity of training samples.

### Methodology 🤖:
 I use the YOLOv8 architecture for training the alpacas detection model. The training process was limited to 50 epochs to accommodate the available computational resources. The training pipeline includes the following steps:

  - Data Preprocessing: Images were resized to a consistent input size suitable for the YOLOv8 architecture. Annotations were processed to match the resized images.

  - Model Configuration: YOLOv8 requires a configuration file specifying the model architecture, hyperparameters, and anchor box information.

  - Training: The model was trained using the prepared dataset and configuration. We monitored metrics such as loss and mAP (mean Average Precision) during training.

### Results 📈 : 
Despite the limited dataset and training resources, the YOLOv8 model shows promising results in detecting alpacas in images. The detection accuracy and precision may not be as high as models trained on larger datasets. 
![results](https://github.com/Elbhnasy/Alpacas_Detection_Yolo8/assets/63622300/89e045b1-a05e-4ca0-99b9-ff66f07be598)


#### Output :



