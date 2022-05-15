# layout-1

-Goal:
This project was to create the layout which **an image is placed in the middle of text contents and the texts wrap around the image according to its shape**.

-Issues:
CSS <u>'float' property with 'shape-around' might work for this project but 'float' won't let the image placed in the middle</u>, so that other method was needed to create the desired layout.

-Solution:
The main content area, where the image was intended to insert in the middle, was divided into two columns by using 'grid'.

 Also the image was vertically cut in half and divided into two pieces. Each cut-half image went into each of the grid area and placed right or left by using 'float'. With this method, the half-cut-images were put together in the middle of the two grid-columns and looked as one image.

 To wrap texts around the image, **'shape-outside: polygon()'** was used.

 



