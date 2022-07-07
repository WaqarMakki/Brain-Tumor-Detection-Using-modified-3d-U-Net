# Brain-Tumor-Segmentation-Using-mofied-3d-U-Net
I worked on Brain Tumor Segmentation as my final year project. In this project we developed a technique where we combined both auto and manual feature extraction.
I compared the results of my new model with simple U-Net model. 
### Results:
IOU-Score on Simple U-Net model:            0.6751
IOU-Score on Modified U-Net model:
        -With Laplacian Feature map:        0.7731
        -With Meijering Feature map:        0.7949
        -With Sharpness x2.5 Feature map:   0.7802
        
Then we selected the model with Meijering Features as it gave the highest mean IOU-Score.

Our Model looked and worked like the one in picture below. The only change is that we used U-Net in place of simple CNN.

![Picture1](https://user-images.githubusercontent.com/53892108/177797477-42244fac-2ec7-4945-b755-d79119305aeb.jpg)
