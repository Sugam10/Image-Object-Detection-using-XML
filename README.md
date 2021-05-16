# Image-Object-Detection-using-XML

## Assignment 

## Requirements

Run pip install -r requirements.txt

## Overview

There are 2 python files 

1. application.py - This python file includes flask, a third-party Python library used for developing web application. This file gets the input from index.html and then calls the image_object_detection.py and gives the input given by the user.
2. image_object_detection.py - This python file first parse the XML file provided by the user and extracts the object name and its bounding box coordinated and then creates the bounding box on the input image provided by the user and saves it using OpenCV Library.

## How to use

Step 1 - Change the path in application.py in line 15 in directory variable to the path where you have cloned the project.

Step 2 - Change the path in image_object_detection.py in line 79 under directory variable to the static folder inside the project.

Step 3 - Now run application.py

Step 4 - An IP address will appear click on it and it will directly let you to the page.

Step 5 - Upload an Image File and XML File and click Submit.

Viola! The output will appear on the same screen with objects detected with bounding box and their name on it. 
