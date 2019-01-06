# Gen_data_imgs-

# Require 
Python 
https://www.python.org/
Augmentor
https://github.com/mdbloice/Augmentor

# How to use 
 
## 1. Step 1 
Put imgs into folder "base_imgs/" to generate with random_distortion, zoom, crop_random, skew in Augmentor - generate1.ipynb 
## 2. Step 2
Rename generated files in "base_imgs/output/" with classID + " - " + ID 
## 3. Step 3 
Put generated files into "data_gen/"
## 4. Step 4 
Generate img with background randomscale with generate2.ipynb. Data will be generate in "data/"
