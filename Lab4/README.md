## Lab 4 – Edge Detection Techniques

### Objectives
- Detect edges in images using gradient-based methods.
- Apply and compare Sobel, Prewitt, and Canny edge detectors.
- Tune thresholds and visualize different edge maps.

###  Key Concepts
- Edges: Boundaries where intensity changes sharply, useful for object detection and recognition.
- Sobel Operator: Computes gradients in the x and y directions using convolution; emphasizes edges with smoothing.
- Prewitt Operator: Similar to Sobel but uses simpler kernels, highlighting horizontal and vertical edges.
-Canny Edge Detector: Multi-stage algorithm involving gradient calculation, non-maximum suppression, and thresholding; considered one of the most robust edge detectors.

### Implementation
- Load the input image in grayscale.
#### Apply:
- Sobel Operator to compute gradient magnitude from x and y directions.
- Prewitt Operator using manually defined kernels.
- Canny Edge Detector with adjustable threshold values.
- Display the original and processed edge maps side by side.

###  Result
- Sobel: Highlighted both horizontal and vertical edges clearly, with some smoothing.
- Prewitt: Detected edges similar to Sobel but with less emphasis on intensity variations.
- Canny: Produced the cleanest and most well-defined edges due to multi-stage processing and threshold tuning.
- By adjusting thresholds, the Canny detector provided flexibility in balancing noise reduction and edge sharpness.

#### Conclusion: Sobel and Prewitt are useful for basic gradient-based edge detection, while Canny provides the most accurate and noise-resistant edge maps.
