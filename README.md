# Image Comparison Script

This script allows you to compare two images and calculate the Structural Similarity Index (SSIM) between them. It can be helpful for tasks like image quality assessment or identifying differences between two similar photos.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV (cv2)
- imutils
- matplotlib
- numpy
- scikit-image

You can install these dependencies by running the following command:

pip install opencv-python imutils matplotlib numpy scikit-image

## Usage

To compare two images, follow these steps:

1. Open a terminal or command prompt and navigate to the directory where the script is located.

2. Run the script using the following command:

python image_comparison.py -f <path_to_first_image> -s <path_to_second_image>


Replace `<path_to_first_image>` and `<path_to_second_image>` with the actual paths to your desired input images.

3. The script will calculate the SSIM between the images and display the result. A higher SSIM score indicates a higher similarity between the images.

4. Additionally, the script will generate visual outputs, including the difference map, thresholded difference map, and rectangles indicating the regions of difference overlaid on the original and modified images.

## Example

Here's an example command to compare two images:

python image_comparison.py -f input_image1.jpg -s input_image2.jpg


This command will compare `input_image1.jpg` and `input_image2.jpg` and display the SSIM score and visual outputs.

## License

This project is licensed under the MIT License. Feel free to modify and use it according to your needs.

## Acknowledgments

This script was inspired by the need to compare images for a game contest that finds differences. It utilizes the Structural Similarity Index (SSIM) algorithm provided by scikit-image.

