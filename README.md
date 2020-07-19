# Computer Vision Pipeline using TinyYolo and MobileNet

The repository contains a Computer Vision Pipeline that takes video input and identifies cars, car-type(HatchBack and Sedan) and the colour of the car.

The pipeline uses keras implementation of tiny-yolo3 model(github.com/allanzelener/YAD2K) for Object Detection and MobileNet model(github.com/keras-team/keras-applications/blob/master/keras_applications/mobilenet.py) for car-type identification and Attribute Classifier from OpenCV for colour identification.

The output of the pipeline generates an excel with number and type of cars identified in each frame of the video.

Let's Keep Coding!
