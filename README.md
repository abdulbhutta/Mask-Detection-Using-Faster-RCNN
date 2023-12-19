# Mask Detection using Faster R-CNN
### Abdul Bhutta
### EE8223 - Deep Learning Final Project

This is a final project for EE8223: Deep Learning

It implements a object detection algorithm, Faster R-CNN, to detect multiple people wearing masks, not wearing a mask, or the mask is worn incorrectly. 

![alt text](https://github.com/abdulbhutta/Mask-Detection-Using-Faster-RCNN/blob/main/Image/Mask_Image.png)

## Getting Started

Please look below on how to run the code or model!

### Prerequisites

Download or Clone this repo.
* Change Path Names, if using Google Colab use the first 7 line of code or if working locally use the last 3 lines. Please update to your paths!
  ```sh
  #Connect to Google Drive
  from google.colab import drive
  drive.mount('/content/drive')
  
  #Locations of images and annotations in google drive
  images = os.listdir('/content/drive/MyDrive/FaceMask_Dataset/images')
  annotations = os.listdir('/content/drive/MyDrive/FaceMask_Dataset/annotations')
  root_dir = '/content/drive/MyDrive/FaceMask_Dataset'
  
  #images = list(sorted(os.listdir('/Users/abdulbhutta/Desktop/Deep Learning/Final_Project/FaceMask_Dataset/images')))
  #annotations = list(sorted(os.listdir('/Users/abdulbhutta/Desktop/Deep Learning/Final_Project/FaceMask_Dataset/annotations')))
  #root_dir = '/Users/abdulbhutta/Desktop/Deep Learning/Final_Project/FaceMask_Dataset'
  ```

### Train/Run the Model

Below is an example of how you Train or Test your own model. You must change the path and import the libraries!

To Train: Go to the Train Section in the Notebook
   ```sh
   Run the Pre-Processing Data Section (5 Cells)
   Run the Training Begins Section (5 Cells)
   ```
To Test: Go to the Testing Model on Test Data Section
   ```sh
   Run the 11 Cells and view the Results
   ``` 
