# Edge_Detection
Detecting edges of an anime scene to work through the basics of image processing.

## Image To Be Processed:
<img src="Images/ImageToBeProcessed.png" width=250>
This image will first be converted to greyscale to reduce the complexity for passing the image through a filter.

## Sobel Filter:
<img src="Images/Filters.PNG" width=250>
The algorithm uses one filter at a time and starts on the top left of the image. The filter gets convoluted with a 3x3 matrix containing the images greyscale values and then it moves the filter one pixel to the right; performing the same process. Once the filter reaches the end, it will move back to the left side of the picture, but one pixel below where the filtering started initially. This filtering process runs until the filter reaches the bottom right of the image.  

## Image After Processing:
