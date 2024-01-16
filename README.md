# Lane Detection System using OpenCV with Hough Transform

## Overview

This project implements a lane detection system using OpenCV with the Hough Transform algorithm. The goal is to identify and highlight lanes on the road in images or video streams. Lane detection is a crucial component in various applications, such as autonomous vehicles and advanced driver assistance systems.

## Dependencies

- Python 3.x
- OpenCV
- NumPy

Install the required packages using the following command:

```bash
pip install opencv-python numpy
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Aashutosh-922/Lane_Detection_CV.git```

2. Navigate to the project directory:

```bash
cd Lane_Detection_CV
```

3. Run the lane detection script:

```bash
python main.py
```

This script uses OpenCV functions and the Hough Transform to process images or video frames and detect lanes.

## Configuration

You can modify the parameters in the `lane_detection.py` script to fine-tune the lane detection algorithm. Adjust parameters such as the Gaussian blur kernel size, Canny edge detection thresholds, and Hough Transform parameters to optimize the performance for different scenarios.

```python
# Lane detection parameters
gaussian_blur_kernel = 5
canny_low_threshold = 50
canny_high_threshold = 150
hough_rho = 2
hough_theta = 1
hough_threshold = 15
hough_min_line_length = 10
hough_max_line_gap = 5
```

Feel free to experiment with these parameters to achieve optimal results based on your input data.

## Sample Output

You can find sample output images in the `output` directory. These images will show the detected lanes overlaid on the original input images.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The implementation is inspired by the computer vision community and OpenCV documentation.
- Special thanks to the open-source contributors for their valuable insights and code contributions.

Feel free to contribute to this project by submitting issues or pull requests. Your feedback is highly appreciated!
