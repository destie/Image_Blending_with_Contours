# Image_Blending_with_Contours
A fun project involving experimentation with the contours module present in OpenCV.

The following code identifies the contours (using edge detection from the OpenCV module) from two separate images and then cycles through each contour to redraw the inner pixels on a new image. This works very well on two aligned images to blend a face, such as two dog faces. 


This repository contains:

**Blending_Code**
This code takes two images, identifies the contours using the Opencv implementation involving edge detection, then iteratively overlays the are inside each subsequent contour based on which contour from which image is larger. 

**Blending_Code_Alternate - Doesn't work as well**
This code takes two images and iteratively cycles between the contours with no regard for what's larger. It doesn't work as well as the first implementation.

**Draw_Area_Inside_Contour_On_New_Image**
This code takes the inside of an area identified by a contour and draws it on a new area. 

**Find_and_Draw_Largest_Contour**
This code identifies the largest contour in an image and draws it.
