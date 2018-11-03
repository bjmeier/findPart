# findPart
Jupyter notebook provides methods for separating a part from a background

Methods include:

- Flood filling
- Color thresholding + countour finding
- Gaussian blur + Canny edge detection + morphological transformation

## Tweak mode (tweak = True)
- Allows parameters to be changed and method selected
- Displays pipeline
- Allows for saving of pipeline summary

## Run mode (tweak = False)
- Sends input image to function
- Returns image with background set to zero

# Platform, python version and packages used:
platform:  
Linux-4.15.0-38-generic-x86_64-with-debian-buster-sid
#41-Ubuntu SMP Wed Oct 10 10:59:38 UTC 2018

python:  
3.6.6 |Anaconda, Inc.| (default, Oct  9 2018, 12:34:16) 
[GCC 7.3.0]

packages:  
cv2: 3.4.3;
numpy: 1.14.4;
json: 2.0.9;
platform: 1.0.8


