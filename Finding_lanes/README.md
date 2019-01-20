### Finding_Lanes

**Simple Lane Line Finder**. Works on an image/video via a combination of color thresholding, smoothing, and a hough lines transform.

**Language-**   Python
**Packages-**   OpenCV
              - Matplotlib
              - Numpy
               
## How it's done...

- import all the useful packages
- convert the image to grayscale
- add gradient to the image to highlight the pixels of the lane lines
- perform “Canny edge detection” to identify edges in the image,( An edge is place where the color or intensity of the image changes         sharply)
- use a technique called a “Hough transform” to find lines in the image that might be the lane lines we are looking for
- apply these lane lines to the original image
- apply all these steps to the video

## TO-DOs

- [ ] make a better algorithm
- [ ] work in different light conditions 


