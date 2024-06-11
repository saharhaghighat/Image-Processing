# Image Processing Tasks

This repository contains solutions for various image processing tasks using Python and OpenCV. The tasks include edge detection, image sharpening, and frequency domain transformations. The solutions are provided as Jupyter notebooks.

## Table of Contents

- [Installation](#installation)
- [Task 1: Edge Detection](#task-1-edge-detection)
- [Task 2: Image Sharpening](#task-2-image-sharpening)
- [Task 3: Cartoonizing an Image](#task-3-cartoonizing-an-image)
- [Task 4: Frequency Domain Transformations](#task-4-frequency-domain-transformations)
- [References](#references)

## Installation

To run the notebooks, you'll need to have Python installed along with the following packages:
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

You can install the required packages using pip:

```bash
pip install opencv-python numpy matplotlib jupyter
```

To start Jupyter Notebook, run:

```bash
jupyter notebook
```

## Task 1: Edge Detection

### Description
This task involves detecting edges in an image using various edge detection filters including Roberts, Prewitt, Sobel (both horizontal and vertical), Laplacian, and LOG. Additionally, edge detection using the Canny algorithm is performed with appropriate threshold values.

### Instructions
- Open the `Task_1_Edge_Detection.ipynb` notebook.
- Follow the steps to load the image and apply different edge detection filters.
- Experiment with different threshold values for the Canny edge detection algorithm.

## Task 2: Image Sharpening

### Description
This task involves sharpening an image using three different methods:
1. Applying a Laplacian sharpening filter.
2. Adding the original image to the result of the Laplacian filter.
3. Using a Gaussian sharpening filter.
4. Applying a LOG (Laplacian of Gaussian) filter.

The parameter alpha is varied to observe its effect on the output images. The differences between the three methods are also explained.

### Instructions
- Open the `Task_2_Image_Sharpening.ipynb` notebook.
- Follow the steps to load the image and apply different sharpening techniques.
- Experiment with different alpha values to see their impact on the images.

## Task 3: Cartoonizing an Image

### Description
This task involves cartoonizing an image using the steps covered in class. The process is also applied to another image of your choice to observe the results.

### Instructions
- Open the `Task_3_Cartoonizing_Image.ipynb` notebook.
- Follow the steps to cartoonize the provided image.
- Apply the same process to another image and compare the results.

## Task 4: Frequency Domain Transformations

### Description
This task involves transforming images into the frequency domain using FFT (Fast Fourier Transform). The logarithm of the absolute value of FFT is displayed using fftshift. Different sigma values are used to observe their effects on the images.

### Instructions
- Open the `Task_4_Frequency_Domain_Transformations.ipynb` notebook.
- Follow the steps to transform the images into the frequency domain.
- Experiment with different sigma values and observe their impact on the images.

## References

- [Jupyter Notebook](https://jupyter.org)
- [OpenCV Documentation](https://docs.opencv.org/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
