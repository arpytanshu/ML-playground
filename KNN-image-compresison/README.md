Using KNN for compressing image.

Each pixel is treated as a data sample.
R, G, B value for each pixel is the feature of each sample.

Now apply KNN with K # of clusters.
The resulting image will have K distinct colors only,
(which will be the most occuring colors in the original image)

Results:


![ref_img](https://github.com/arpytanshu/ML-playground/blob/master/KNN-image-compresison/ref_img.png)


