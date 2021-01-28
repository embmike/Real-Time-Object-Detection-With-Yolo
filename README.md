# Real-time object detection with Yolo
This sample software uses the Yolov3 project to recognize traffic objects and their bounding boxes in videos.

**Yolov3 writes about this**
We apply a single neural network to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.
    
    
### Examples

+ **Detects a car and a truck in a video**   
![Traffic objects 1](/images/car_and_truck.PNG "Detects a car and a truck in a video")    
    
+ **Detects two cars in a video**   
![Traffic objects 2](/images/two_cars.PNG "Detects to cars in a video") 

   
   
## Important files
- **traffic_object_detection.py** : The application for recognizing objects
- **darknet.py** : The Yolov3 software
    
    
## Installation and usage
Clone the repository
```sh
$ cd <your workspace folder>
$ https://github.com/embmike/Real-Time-Object-Detection-With-Yolo.git
```    
   
Download the cnn-weights to the repository folder    
https://pjreddie.com/media/files/yolov3.weights

Install data science tool   
[Anaconda](https://www.anaconda.com/)

Then create a new anaconda environment and activate
```sh
$ conda env create -f yolov3.yml
$ conda activate yolov3
```

Open comman windows and start application
```sh
$ cd <your repository path>\Real-Time-Object-Detection-With-Yolo
$ <your anaconda path>\Anaconda3\envs\yolov3\python traffic_object_detection.py --video <your video>.mp4
```
    
## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
