# Cartoonizing the Image

This is a Python script that converts an image into a cartoon-style image using OpenCV and NumPy. The script applies a bilateral filter to reduce the color palette, detects and emphasizes the edges using Canny edge detection, and then merges the edges with the filtered image to produce a cartoon-style image. The script also includes an optional argument to adjust the intensity of the edge lines.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib (for displaying the image)

## Usage

1. Clone this repository or download the `cartoonize.py` file.
2. Install the required packages using pip: `pip install opencv-python numpy matplotlib`
3. Run the script with the following command: `python cartoonize.py path/to/input_image path/to/output_image [optional: edge_intensity]`

Example:
python Cartoon_Master.py


The `edge_intensity` argument is optional and controls the intensity of the edge lines. The default value is 100.

## License

This code is released under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

This script was inspired by the following resources:

- [Cartooning an Image using OpenCV - Python](https://www.geeksforgeeks.org/cartooning-an-image-using-opencv-python/) by GeeksforGeeks
- [How to Cartoonize an Image using OpenCV in Python](https://www.analyticsvidhya.com/blog/2021/06/cartoonize-an-image-using-opencv-in-python/) by Analytics Vidhya
