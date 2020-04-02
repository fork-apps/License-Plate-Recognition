# License Plate Recognition
## The project will be divised into 4 steps :
* **Step 1 : Licence plate detection**<br/>
In order to detect licence, in this project I used YoloV3 object detection architecture based on convolution neural networks.

* **Step 2: Licence plate segmentation**<br/>
The input is the image of the plate, I have to extract the character in input images. The result of this step, being used as input to the recognition phase. It is of great importance in a system of automatic reading of number plates.

* **Step 3: Licence plate recognition**<br/>
The recognition CNN model built by Keras has input from the images characters obtained at the end of the segmentation phase. The learning model that will be used for to read an image characters and to render the corresponding character.

* **Step 4: Reformat License Plate**<br/>
The plate can be splited to one or two part. So, reformat phase will be used to determine license plate which one or two parts


## Dependencies
* Keras
* Skimage
* Imutils
* Opencv3
* Numpy

## Quick start
```python example.py -i image_path```

## ANPR that Works
1. **Works on Plate with 2 rows**
<p align="center">
  <img width="600" height="300" src="https://github.com/buiquangmanhhp1999/License-Plate-Recognition/blob/master/example4.png">
</p>

2. **Works on Plate with 1 row**
<p align="center">
  <img width="600" height="300" src="https://github.com/buiquangmanhhp1999/License-Plate-Recognition/blob/master/example5.png">
  
3. **Works when Plate is at angle**
<p align="center">
  <img width="600" height="300" src="https://github.com/buiquangmanhhp1999/License-Plate-Recognition/blob/master/example2.png">
</p>

