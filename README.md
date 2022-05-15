# Centered image with texts around it

This project was to create a layout which **an image is placed in the middle of text contents and the texts wrap around the image according to its shape**.

## Issues
CSS 'float' with 'shape-outside: polygon()' can work for this project but the issue was that 'float' won't let the image placed in the middle, only left or right. So other method was needed to create the desired layout.

## Solutions
**The main content area**, where the image was intended to insert in the middle, **was divided into two columns by using 'grid'** ('flex' will work as well).

 Also **the image had to be vertically cut in half and divided into two pieces**. Each cut-half image went into each of the grid columns and placed right or left by using 'float'.  With this method, **the half-cut-images were put together between two grid-columns just like one image and automatically looked centered as well**.

Then **'shape-outside: polygon()'** was used to wrap texts around the image. 
 
 # Thoughts
 
This project was fun to experiment. It was good to see another possiblility of what 'grid' ('flex', too) can offer. Also '{shape-ouside: polugon()}' gives text design more flavours - like it very much!.
 
One thing that I wondered was how to write in 'alt' attribute for the images. Since the image had to split into halves, I wasn't so sure about what to wrote for each. Perhaps, 'an half image of xxxx' ??!??!? Any recommendations?


 



