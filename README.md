# yolo-object-detection
an interface to the Yolo object detection network

# User guide

## Collecting data
Start the robot. On your devpc run
```bash
rosrun image_view image_view image:=/hero/head_rgbd_sensor/rgb/image_raw # or substitute your image topic
```
Move the robot around using rviz and the gui server and when you want to save an image right-click on the image view.

## Annotating data
Use [Roboflow](https://roboflow.com) for annotating data.

## Training the model

## Using the model
