# Mars Crater Detection and Segmentation with MaskRCNN

![](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/gitex.PNG)

#### Dependencies 


Detection of craters on planetary surface is very crucial for the better understanding of planet topography. It is also important for the selection of landing sites of various lander mission, path planning for rover missions. This project is about application of deep learning method for detection and semantic segmentation of craters in an image. Model trained using transfer learning on pretrained MaskRCNN model. Overall project can be devided into four parts as follow:-    

1. [Data Preparation](https://github.com/mymultiverse/Mask_RCNN/edit/master/samples/crater#Data-Collection-and-Training-Validation-data-preparation)

2. [Data Inspection](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/inspect_crater_data.ipynb)

3. [Training](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/train.ipynb)

4. [Testing](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/inspect_crater_model.ipynb)

With splash.py the trained model was tested on video, although it was only trained with Mars data, learned model able to detect craters on the lunar surface as well.

Mars                       |  Moon
:-------------------------:|:-------------------------:
[![](https://img.youtube.com/vi/JdmykAEQing/0.jpg)](https://youtu.be/JdmykAEQing) |                                           [![](https://img.youtube.com/vi/FRbNQiYLvgo/0.jpg)](https://youtu.be/FRbNQiYLvgo)

#### Data Collection and Training-Validation data preparation 

Image data collected from the [sources](Dataset-Sources) and annotated with [VIA](http://www.robots.ox.ac.uk/~vgg/software/via/via.html) tool to get json file. Which looks like:- 

![](https://github.com/mymultiverse/Mask_RCNN/blob/master/samples/crater/viaex.PNG)


