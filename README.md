# How to get the lung-only DRR and bone-only DRR from CT images ? 

### 1. Use rule-based methods (Hounsfield unit) to generate lung and bone masks from CT images.

![image](https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_1.png)


### 2. Use these masks to training segmentation model, and follow Step A to Step D.
####  Step A: Use madel to get lung mask from CT image.
####  Step B: Clean all information, only save body contour. 
####  Step C: Use lung mask to segmentation lung image from CT image.
####  Step D: Mix lung image and body image.
<br>
![image](https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_2.png)


### 3. Repeat Step A to Step D for all CT images.

![image](https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_3.png)


### 4. Sum all segmentation images.
![image](https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_4.png)


### 4. Sum all segmentation images.
![image](https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_4.png)


### 5.The GIF show the process of sum images.
![image, images](https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_4.png, https://github.com/lzy0934/CT-Image-Research/blob/master/images/step_4.png)
