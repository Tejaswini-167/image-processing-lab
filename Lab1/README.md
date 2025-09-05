### Lab 1 – Basic Image Reading and Color Space Conversion

###Objectives
- Learn to read an image using OpenCV.
- Convert images between different color spaces (BGR, RGB, Grayscale, HSV).

## Display processed images for visual understanding.

### Key Concepts
- BGR vs RGB: OpenCV loads images in BGR format, while most libraries use RGB. Conversion ensures correct color representation.
- Grayscale Conversion: Reduces a 3-channel image to a single channel, simplifying processing.
- HSV Conversion: Represents images in Hue, Saturation, and Value components, useful for color-based processing.

### Implementation
- Load the input image using cv2.imread().
- Convert BGR → RGB, BGR → Grayscale, and BGR → HSV using OpenCV functions.
- Display all versions of the image to observe the differences.

### Result
- Original BGR Image: Displayed in OpenCV’s default format (may look slightly off in colors).
- RGB Image: Correctly displayed colors for visualization.
- Grayscale Image: Converted to single-channel black-and-white format.
- HSV Image: Represented image using hue, saturation, and brightness components.
