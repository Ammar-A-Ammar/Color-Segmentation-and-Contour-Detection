# Color-Based Object Detection

This project utilizes OpenCV and NumPy to detect objects of specific colors (red and green) in images.

It then draws **bounding boxes** around these detected objects for visualization.

## Features

* Load images and convert them to RGB format.
* Define color ranges for red and green in RGB.
* Create masks to isolate red and green objects in the images.
* Detect contours of the masked objects.
* Draw bounding boxes around detected objects.

## Requirements

* Python 3.x
* OpenCV
* NumPy

## Installation

1. Clone the repository:

``` bash
git clone https://github.com/Ammar-A-Ammar/Color-Segmentation-and-Contour-Detection.git
```

2. Navigate to the project directory:

``` bash
cd color-object-detection
```

3. Install the required packages:

``` bash
pip install opencv-python numpy
```

## Usage

1. Place your images in the project directory.
2. Modify the image paths in the script if necessary:

``` python
image1 = cv2.imread('colors_circles.png')
image2 = cv2.imread('colors_circles_big.png')
image3 = cv2.imread('colorstar-opt.jpg')
image4 = cv2.imread("colors_name_verybig.webp")
image5 = cv2.imread("cat.jpeg")
```

3. Run the script:

``` bash
python color_detection.py
```

## Contributing

Feel free to open issues or submit pull requests for improvements and bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
