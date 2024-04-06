# Brain Tumor Segmentation

## Overview

This project, developed by **Ishaan Buch** and **Jaineet Shah**, tackles the critical challenge of segmenting brain tumors from MRI images. Utilizing OpenCV, Matplotlib, and Numpy, we've devised a methodology that segments tumors with precision, aiding in the diagnosis and treatment planning for brain tumors. This project outlines a basic segmentation process, highlighting the potential of image-processing techniques in medical diagnosis.

## Segmentation Process

The process of segmenting a brain tumor from MRI images involves several key steps:
1. **Converting to Grayscale:** Utilize OpenCV to convert MRI images to grayscale for further processing.
2. **Applying Median Filter:** Implement median filtering to reduce noise without sacrificing edges.
3. **Edge Detection using Sobel Filters:** Use Sobel filters to highlight edges, essential for detecting the boundaries of a tumor.
4. **Thresholding the Intensity:** Apply thresholding to create binary images, simplifying the segmentation process.
5. **Performing Morphological Opening:** Use erosion followed by dilation to remove noise.
6. **Isolating the Tumor with the Watershed Algorithm:** Employ the watershed algorithm to precisely segment the tumor.

![Tumor Segmentation Process](Figure_8.png)

*Figure: Segmentation results showing the isolated tumor.*

## Conclusion

Brain tumor segmentation is pivotal for early diagnosis and effective treatment planning. The methodology presented here showcases a fundamental approach to segmentation using image processing techniques. Future work can explore more advanced methods such as thermal imaging, fuzzy clustering, and artificial neural networks to enhance segmentation accuracy and efficiency.

## Libraries Used

- **OpenCV:** For image manipulation and processing.
- **Matplotlib:** To display images.
- **Numpy:** For matrix manipulation and operations.

## How to Use

To replicate this segmentation process:
1. Ensure you have Python installed along with the libraries mentioned above.
2. Clone this repository and navigate to the project directory.
3. Run the script with an MRI image of your choice as input.

## Contributing

We welcome contributions and suggestions to improve the segmentation process further. Please feel free to fork the repository, make changes, and submit a pull request.

## Acknowledgments

Special thanks to the academic and research community for providing the tools and knowledge necessary to undertake this project.
