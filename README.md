## Author: Grant Norrie
## Date 2021/02/05
## Title: Pedestrian Extractor

## Description:

   This program takes in a video chosen by the programmer,
   Samples the video for frames at a user defined interval 
   (allows for processing on less powerful computers) and 
   then optionally displays displays the images with 
   bounding boxes, confidences as well as categories of 
   ALL the objects found in the image using the YOLOV3 
   neural network. Instances where people are found are
   stored in a user defined path, with the corresponding 
   video time

## Instructions for usage:
   1: Include selected video name current folder
   2: Fill in fram rate variable
   3: Choose frame increment rate
   4: Choose if you would like to display images (true/false)
   5: Set the path of where the output images will be saved  (folders will no automaticaly be created)
   6: Run :)
 
## Additional Notes:
  -This script uses the pretrained YoloV3 network (https://pjreddie.com/darknet/yolo/)
