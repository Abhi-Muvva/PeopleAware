# YOLO Model for People Detection
This repository contains code that uses the YOLO (You Only Look Once) model to detect people in images from the COCO (Common Objects in Context) dataset. The modified code focuses on detecting and labeling people within the images.

## Prerequisites
Before running the code, make sure you have the following:

* Python environment with required packages installed
* YOLO weights and configuration files (yolov4.weights and yolov4.cfg)
* COCO class names file (coco.names)
* An image to be used for detection (image.jpg)

## Modifications Made
The original code provided is adapted to specifically detect people in the images using the COCO dataset. Here are the key changes made to the code:

* Class Index for People:
The class name "person" in the COCO dataset corresponds to class index 0. The code is updated to consider only detections of the "person" class.

* Filtering and Labeling:
The code now filters out detections that are not of the "person" class. It labels the detected people as "Person" and displays the confidence score and frames per second (FPS) information.

## Usage
Clone the repository to your local machine: git clone https://github.com/Abhi-Muvva/PeopleAware.git
Place the YOLO weights, configuration, class names, and image files in the appropriate directory.

- Run the modified code using a Google Collab
