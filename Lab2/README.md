## Lab 2 – Image Enhancement Techniques

### Objectives
- Enhance image quality using contrast and brightness adjustment techniques.
-Apply Histogram Equalization and Contrast Stretching.
-Compare enhancement results on different image datasets.

### Key Concepts
- Histogram Equalization: Redistributes pixel intensity values to enhance global contrast.
- Contrast Stretching: Expands the intensity range (0–255) to improve visibility of details.
- Comparison: Different methods highlight strengths and limitations depending on the dataset.

### Implementation
- Load the image in grayscale.
- Apply Histogram Equalization using OpenCV’s built-in function.
- Implement a Contrast Stretching function to normalize pixel values.
- Visualize the original and enhanced images side-by-side for comparison.

### Result
- The Original Image had low contrast.
- The Histogram Equalized Image showed better global contrast and brightness distribution.
- The Contrast Stretched Image displayed improved clarity by spreading pixel values across the full range.
- Overall, histogram equalization provides balanced enhancement, while contrast stretching is dataset-dependent but effective for improving both dark and bright regions.
