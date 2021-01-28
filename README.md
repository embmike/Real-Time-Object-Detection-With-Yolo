# Real-time object detection with Yolo
This excample software using the Yolov3 project to detects traffic objects and they boundig boxes.

**Yolov3 writes about this**
We apply a single neural network to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.
    
    
### Examples

+ **Detects a car and a truck in a video**   
![Traffic objects 1](/images/car_and_truck.PNG "Detects a car and a truck in a video")    
    
+ **Detects two cars in a video**   
![Traffic objects 2](/images/two_cars.PNG "Detects to cars in a video") 

   
   
## Important files
- **1_Load_and_Visualize_Data.ipynb** : Learn to create a data loader and visualize the data
- **data_load.py** : The Data loader
- **2_Define_the_Network_Architecture.ipynb** : Load, train and validate the convolutional neural network.
- **models.py** : The Convolutional neural network
- **3_Facial_Keypoint_Detection_Complete_Pipeline.ipynb** : Test and compare the model with the cascade classifier.
    
    
## Installation and usage
Clone the repository
```sh
$ cd <your workspace folder>
$ https://github.com/embmike/Real-Time-Object-Detection-With-Yolo.git
```    
   
Download the (cnn-weights)[https://pjreddie.com/media/files/yolov3.weight] to the repository folder

Install data science tool   
[Anaconda](https://www.anaconda.com/)

Then create a new anaconda environment and activate
```sh
$ conda env create -f yolov3.yml.yml
$ conda activate yolov3
```
    
    
## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
