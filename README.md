# Pan Card Tampering Detection

This repository contains a Jupyter notebook for detecting tampering in PAN card images using image processing techniques. The project utilizes OpenCV and scikit-image to compare the structural similarity of PAN card images and determine if any tampering has occurred.

## Installation

To run the notebook, you need to have Python and the necessary libraries installed. You can install the required libraries using pip:

```
pip install numpy opencv-python scikit-image matplotlib
```
## Usage
Clone The Repository
```
git clone https://github.com/IIITManjeet/Pan_Card_Tampering.git
cd Pan_Card_Tampering
```
Open with Jupyter Notebook
```
jupyter notebook main.ipynb
```
## Project Structure
- main.ipynb: The main Jupyter notebook containing the code for PAN card tampering detection.
* images/: Directory containing sample PAN card images used for testing the tampering detection algorithm.
+ requirements.txt: File listing the required libraries for the project.

## Methodology 
The project uses the following steps to detect tampering in PAN card images:
- Load the original and test images.
- Convert the images to grayscale.
- Compute the Structural Similarity Index (SSIM) between the original and test images.
- Highlight the differences between the images to visualize potential tampering.

## Result
The notebook includes visualizations of the original, test, and difference images along with the SSIM score. Higher SSIM scores indicate higher similarity between the pictures, while lower scores suggest possible tampering.
