# Optical Flow Motion Detection Project

This repository contains code for an algorithm developed to detect object motion in the presence of camera motion using Optical Flow and Python.

## Aim of the Project
The aim of this project was to develop an algorithm capable of detecting object motion even in scenarios where the camera itself is in motion. By utilizing Optical Flow techniques and various image processing methods, the algorithm is designed to accurately identify and track moving objects within a video stream.

## Components of the Project
1. **optical_flow.ipynb**: This notebook includes the computation of Optical Flow, which is the core technique used for motion detection. It contains the implementation of Optical Flow algorithms and the calculation of motion vectors.
   
2. **classification_and_visualisation.ipynb**: This notebook encompasses the remaining components of the project. It covers motion segmentation using customized filters and morphology operations, object visualization, and detection refinement using techniques such as Histogram of Oriented Gradients (HOG) and Intersection over Union (IoU).

3. **OpenCV_exercise.ipynb**: This notebook contains exercises conducted at the start of the project to familiarize with OpenCV library and basic image processing techniques.

## Usage
To use the code in this repository, simply clone the repository to your local machine and open the Jupyter notebooks using your preferred Python environment. Follow the instructions and comments within the notebooks to understand and run the code.

## Dependencies
This project requires the following Python libraries:
- OpenCV
- NumPy
- Matplotlib

Install these dependencies using pip if they are not already installed:
pip install opencv-python numpy matplotlib

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as needed.
