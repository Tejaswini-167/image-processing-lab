## Lab 3 – Image Filtering and Smoothing

### Objectives
- Understand how to reduce image noise using different filtering techniques.
- Generate noisy images using Gaussian Noise and Salt & Pepper Noise.
- Apply Gaussian, Median, and Bilateral filters to observe their effectiveness.

### Key Concepts
- Gaussian Noise: Random noise following a normal distribution, common in natural images.
- Salt & Pepper Noise: Randomly scattered white and black pixels, often caused by transmission errors.
- Gaussian Filter: Smooths images by averaging neighboring pixels with Gaussian weights (good for Gaussian noise).
- Median Filter: Replaces each pixel with the median of its neighborhood (very effective for Salt & Pepper noise).
- Bilateral Filter: Preserves edges while reducing noise by considering both spatial and intensity differences.

### Implementation
- Load an image in grayscale.
- Add Gaussian noise and Salt & Pepper noise to create degraded images.

#### Apply:
- Gaussian Blur to smooth Gaussian noise.
- Median Filter to clean Salt & Pepper noise.
- Bilateral Filter to denoise while preserving edges.
- Display and compare original, noisy, and filtered images.

### Result
- Original Image: Clean input for reference.
- Gaussian Noisy Image: Blurred and grainy.
- Gaussian Filter: Reduced Gaussian noise but slightly blurred edges.
- Bilateral Filter: Reduced Gaussian noise while keeping edges sharper.
- Salt & Pepper Noisy Image: Random black and white pixels visible.
- Median Filter: Most effective in removing Salt & Pepper noise without blurring.

####  Conclusion: Different filters are suited for different noise types—Gaussian filters handle Gaussian noise well, Median filters are ideal for Salt & Pepper noise, and Bilateral filters balance denoising with edge preservation.
