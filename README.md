# Difference Of Gaussians
### Implementation of difference of gaussians (Extended & Filtered)

Exploring the world of gaussians as a low pass filter which can eliminate high frequencies which in image processing corresponds to edges.

# 1) Extended DoG
It works by simply subtracting 2 gaussians (multiplied by a sharpening factor) that convolve on the whole image, the effect can be further stylized by thresholding the final result.
Increasing the sharpeness factor allow the filter to detect more edges, however it introduces a new problem that you can clearly see in the picture.
