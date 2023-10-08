# Motion-Based Multi-Object Tracking

This project is a MATLAB-based implementation of a motion-based multi-object tracking system using Kalman filters and blob analysis. The code processes video input, detects moving objects, and tracks their positions over time.

![Multi-Object Tracking](https://github.com/Quan20021511/Digital_Clock/assets/129273695/2c48227a-871d-43cd-b883-be871945fa51)

## Features

- **Object Tracking:** The script detects and tracks moving objects in a video stream.
- **Kalman Filtering:** Kalman filters are used to predict and correct object positions.
- **User-Friendly:** The code is well-commented and structured for ease of understanding and modification.

## Prerequisites

Before running the code, ensure you have the following:

- [MATLAB](https://www.mathworks.com/products/matlab.html) with Image Processing Toolbox.

## Usage

1. Clone this repository to your local machine.

2. Open MATLAB and navigate to the repository's directory.

3. Open the `MotionBasedMultiObjectTrackingExample.m` script.

4. Modify the script or input video file path if needed.

5. Run the script to start object tracking.

## Code Structure

- `MotionBasedMultiObjectTrackingExample.m`: The main script that performs object tracking.
- `setupSystemObjects.m`: Initializes video input and output objects.
- `initializeTracks.m`: Creates an empty array of object tracks.
- `detectObjects.m`: Detects moving objects in each frame.
- Other helper functions: Functions for prediction, assignment, updating tracks, and displaying results.

## Contributing

Contributions to this project are welcome! If you have suggestions for improvements or additional features, please create a pull request.


## Author

- [Nguyen Duc Quan](https://github.com/Quan20021511)

Enjoy object tracking with MATLAB!
