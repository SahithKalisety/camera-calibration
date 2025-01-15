## Camera Calibration and RealSense Image Capture

- This repository contains Python scripts for camera calibration, image capture using Intel RealSense cameras, and managing the depth and color streams from the camera. The project is ideal for applications requiring accurate image calibration and depth data from RealSense cameras.

## Features

- 1.Camera Calibration:

Calibrates the camera using a chessboard pattern.
Saves calibration matrices and distortion coefficients for future use.
Computes reprojection error for validation.

- 2.Image Capture:

Captures color and depth images using an Intel RealSense camera.
Saves images upon user command ('s' key).

- 3.RealSense Camera Interface:

Configures and manages Intel RealSense camera streams.
Provides depth and color data for real-time applications.