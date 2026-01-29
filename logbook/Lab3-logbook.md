# Lab 3 Logbook — Intensity Transformation & Spatial Filtering

## Task 1 — Reading and Viewing the Image

### Command:
Task 1.1
```matlab
clear all
imfinfo('assets/breastXray.tif')
f = imread('assets/breastXray.tif');
imshow(f)
