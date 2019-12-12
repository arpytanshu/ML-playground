## Extracting Histogram of gradients from satellite images and train a SVC classifier.
Use the trained classifier for detecting the presence of objects in satellite iamges.

Aim is to detect the presence of large ships in satellite image
Dataset:  
Image chips from satellite imagery  
2800 (80x80) RGB images labelled with either a “ship” or “no-ship”  
Pixel value data for each 80x80 image – stored as a list of 19200 integers  

### Original Image
![ref_image](https://github.com/arpytanshu/ML-playground/blob/master/HOG-SVM-detect_ship_satellite_image/input/scenes/sfbay_1.png)
  
### Original Images chipped from satellite images  
![ref_image](https://github.com/arpytanshu/ML-playground/blob/master/HOG-SVM-detect_ship_satellite_image/orig.png)

### Visualization of HOG Features extracted from images  
![ref_image](https://github.com/arpytanshu/ML-playground/blob/master/HOG-SVM-detect_ship_satellite_image/hog_features.png)



