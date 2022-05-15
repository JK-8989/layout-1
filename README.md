# Polygon shape with texts around it

This project was to create a layout which **an image is placed in the middle of text contents and the texts wrap around the image according to its shape**.

## Issues
CSS 'float' with 'shape-outside: polygon()' can work for this project but 'float' won't let the image placed in the middle, so that other method was needed to create the desired layout.

## Solutions
**The main content area**, where the image was intended to insert in the middle, **was divided into two columns by using 'grid'** ('flex' will work as well).

 Also **the image was vertically cut in half and divided into two pieces**. Each cut-half image went into each of the grid area and placed right or left by using 'float'.  So... with this method, **the half-cut-images were put together in the middle of the two grid-columns and looked as one image and centered**.

 And then **'shape-outside: polygon()'** was used to wrap texts around the image. 

 



