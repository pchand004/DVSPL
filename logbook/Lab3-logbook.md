# Lab 3 Logbook — Intensity Transformation & Spatial Filtering

## Task 1 — Reading and Viewing the Image

### Command:
Task 1.1
```matlab
clear all
imfinfo('assets/breastXray.tif')
f = imread('assets/breastXray.tif');
imshow(f)

Task 1.2
f(3,10)             % print the intensity of pixel(3,10)
imshow(f(1:241,:))  % display only top half of the image

ans =

  uint8

   28

Task 1.3
>> [fmin, fmax] = bounds(f(:))

fmin =

  uint8

   21


fmax =

  uint8

   255
