# Cartoonify Image using OpenCV

This repository contains a Python script that uses OpenCV to apply a cartoon effect to an input image. The script converts the input image into a cartoon-like representation by detecting edges, applying smoothing techniques, and preserving sharp edges. The resulting cartoonified image is displayed using matplotlib.

## How to Run

1.  Install the required libraries:
    
    -   OpenCV
    -   numpy
    -   imageio
    -   matplotlib
    -   tkinter
    -   PIL
    
    You can install these libraries using `pip`:
    
    Copy code
    
    `pip install opencv-python numpy imageio matplotlib pillow`
    
2.  Clone or download this repository to your local machine.
    
3.  Make sure you have an image that you want to cartoonify. Update the `ImagePath` variable in the Python script with the path to your image.
    
4.  Run the Python script using any Python IDE or from the command line:
    
    Copy code
    
    `python cartoonify_image.py`
    
5.  A graphical user interface (GUI) will open, allowing you to choose the image file you want to cartoonify. After selecting the image, the script will process it and display the original, grayscale, smoothed, edge-detected, and cartoonified versions of the image using matplotlib.
    
6.  You can close the GUI window to exit the application.
