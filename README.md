# ROS2_HUMBLE_WITH_CAMERA
# Face YOLO - ROS 2 Package

## Overview

The `face_yolo` package is a ROS 2 implementation that integrates YOLO (You Only Look Once) for real-time face detection. This package provides tools to detect faces using deep learning models within a ROS 2 environment.

## Features

- Real-time face detection using YOLO.
- ROS 2 compatible package with launch files.
- Modular structure for easy integration and extension.
- Testing scripts for maintaining code quality.

## Installation

### Prerequisites

Ensure you have the following installed:

- ROS 2 Humble (or compatible version)
- Python 3
- YOLO dependencies (OpenCV, PyTorch, etc.)

### Clone and Build

```sh
cd ~/ros2_ws/src
git clone https://github.com/yourusername/face_yolo.git
cd ~/ros2_ws
colcon build --packages-select face_yolo
source install/setup.bash
```

## Usage

### Launch the Node

To start face detection, run the following command:

```sh
ros2 launch face_yolo launch.py
```

### Running Tests

To check code quality and run tests:

```sh
colcon test --packages-select face_yolo
```

## Directory Structure

```
face_yolo/
│── face_yolo/
│   ├── __init__.py
│   ├── yolo.py
│── launch/
│   ├── launch.py
│── resource/
│── test/
│   ├── test_copyright.py
│   ├── test_flake8.py
│   ├── test_pep257.py
│── package.xml
│── setup.py
│── setup.cfg
```

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is licensed under the MIT License.

## Author

[Pritesh](https://github.com/yourusername)

Robotics Engineer 
