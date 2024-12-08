# FaceDetection-MATLAB# MATLAB Face Detection Project  

This project detects faces in an image using MATLAB's **CascadeObjectDetector**. It employs the Viola-Jones algorithm for face detection and marks the detected faces with bounding boxes.  

---

## Features  
- Detects faces in static images.  
- Dynamically resizes images larger than 320 pixels in width.  
- Highlights detected faces with bounding boxes.  

---

## Requirements  
- MATLAB (R2024a or older recommended).  

---

## Usage  
1. Place your input images in the `sample_images` folder.  
2. Update the `face_detection.m` script to reference your image file in the `sample_images` folder.  
   ```matlab
   the_Image = imread('sample_images/your_image.jpg');

