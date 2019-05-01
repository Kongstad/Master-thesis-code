# Repository regarding Master Thesis
Github containing python code written as a part of my master thesis pipeline.
This is a small demonstration.

### There are 4 jupyter files indicative of the process from obtaining satellite imagery to producing a training result through the VGG16 network.

Throughout this process more than 30 different scripts where created to produce 3 different machine learning methods. They all require the data fed in different ways and several scripts were made to stack images together for multi source input to the algorithms. All of these scripts are not available here. Rather a streamlined version of the pipeline that generates the best results so far.

[1. Sentinel-2 image download.](https://github.com/Kongstad/mt/blob/master/notebooks/sentinel2_download.ipynb)

[2. Slicing image patches.](https://github.com/Kongstad/mt/blob/master/notebooks/S2_slice_patches_categorical.ipynb)

  [2.1 db_import_sp.](https://github.com/Kongstad/mt/blob/master/notebooks/db_import_sp.ipynb)
  
[3. VGG16 model and results.](https://github.com/Kongstad/mt/blob/master/notebooks/vgg16_cnn.ipynb)



Pip Freeze file for module control is listed in requirements.txt


