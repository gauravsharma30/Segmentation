
# Human Segmentation using U-Net

## Overview
This repository focuses on human segmentation using the U-Net architecture, a convolutional neural network well-suited for semantic segmentation tasks. Human segmentation has applications in various fields, such as video editing, virtual reality, and human-computer interaction.


## Introduction
Human segmentation involves delineating human figures from the background in images or videos. The U-Net architecture, with its contracting and expansive paths, is particularly effective for this task.



## Dataset
UP-3D data set is used for this project. More specially UP-S31 containing 8515 images divided as images and masks.
Dataset link : https://files.is.tuebingen.mpg.de/classner/up/#datasets

For Project purpose 1000 images and masks were used after uploading to google drive. Below directory structure was used:

- Data 
    - Images
    - Masks

 ![Unknown](https://github.com/gauravsharma30/Segmentation/blob/main/image/image%20and%20mask.png)



## Model Architecture
U-Net is a convolutional neural network architecture designed for semantic segmentation. It consists of a contracting path, a bottleneck, and an expansive path. The architecture is symmetrical, and the expansive path mirrors the contracting path, which helps in capturing context at multiple scales.
![image](https://github.com/gauravsharma30/Segmentation/blob/main/image/unet.png)

## Results
Below are the images showing Predicition , Ground Truth and Actual Image after 40 epochs
![image](https://github.com/gauravsharma30/Segmentation/blob/main/image/result%20after%2040%20epoch.png)

Predicted results were good for normal background subjects, and poor result was generated for image with complex background(3rd image). Results can be improved by training more data and fine tuning the results.


## License
[MIT](https://choosealicense.com/licenses/mit/)

