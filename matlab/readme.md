## Image denoising(que1.m)
Use "leena_noisy.jpg" for the experiment.

![](images/leena_noisy.jpg)

Generate gaussian filters and apply it on the image using various sigma values.
 
## Template matching(que2.m)
### Template "where-is-waldo.jpg"
![](images/where-is-waldo.jpg)
### Target image "waldo.jpg"
![](images/waldo.jpg)

- Find the location of the target image in template image using normalized cross correlation

## Sobel edge detection(que3.m)
1. Define sobel kernels
2. Apply kernels and find the edges
### Test image
![](images/image1.jpg)

If possible write your own code for convolution and correlation

## Hough Transform(que4.m)
1. Use sobel to find the threshold
2. Use canny edge detection on the input image
3. Define houghVotes() function
4. Define houghPeaks() function
5. Define drawHoughLines() function

- Apply hough transform on this image<br>
![](images/image2.png)
- Output should look something like this<br>
![](results/houghLines.jpg)
