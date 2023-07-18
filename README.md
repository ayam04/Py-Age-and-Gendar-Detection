# Py-Age-and-Gendar-Detection

This is a Python script for real-time age and gender detection using OpenCV and pre-trained deep learning models. It utilizes a combination of face detection, age prediction, and gender classification to estimate the age and gender of individuals in a live video stream.

## Requirements

- OpenCV (version 3.4.2 or later)
- Pre-trained models:
  - `opencv_face_detector.pbtxt` and `opencv_face_detector_uint8.pb` (for face detection)
  - `age_deploy.prototxt` and `age_net.caffemodel` (for age prediction)
  - `gender_deploy.prototxt` and `gender_net.caffemodel` (for gender classification)

## Usage

1. Clone the repository and navigate to the appropriate directory.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Download the pre-trained models and place them in the `models` directory.
4. Run the script using the command `python age_gender_detection.py`.
5. The script will open a live video stream with age and gender overlays on detected faces.
6. Press 'q' to exit the program.

## Results

The script uses a combination of deep learning models to accurately predict the age and gender of individuals in real-time. The predicted age range is classified into 8 categories, and the gender is classified as male or female.

## Credits

- This script was adapted from the tutorial by [Murtaza's Workshop - Robotics and AI](https://www.youtube.com/c/MurtazasWorkshopRoboticsandAI) on YouTube.
- The pre-trained models used in this script are available from the OpenCV repository.

Feel free to explore and modify the script to suit your specific requirements.
