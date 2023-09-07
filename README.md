# Karate-Pose-Estimation

This repository contains code for performing Karate pose estimation using the MediaPipe library and a pre-trained machine learning model.

## Introduction

Pose estimation is the task of detecting and tracking the positions of key points on a person's body, such as the shoulders, elbows, and knees, in an image or video. In this project, we use the MediaPipe library to perform real-time pose estimation and then use a machine learning model to make predictions based on the detected pose.

## Requirements

Before running the code, make sure you have the following dependencies installed:

- Python
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- NumPy (`numpy`)
- Joblib (`joblib`)

You can install these dependencies using `pip`:
pip install opencv-python mediapipe numpy joblib


## Usage

1. Clone this repository to your local machine:
git clone https://github.com/Mstf000/Karate-Pose-Estimation.git


2. Change the working directory to the repository folder:
cd Karate-Pose-Estimation


3. Download the pre-trained machine learning model (`random_forest_model.pkl`) and place it in the repository folder.

4. Run the code by executing the Python script:
python pose_estimation.py


5. The code will open a video file (`kata.mp4` by default) and perform pose estimation on each frame. The predicted outcome will be displayed on the video.

6. To exit the application, press the 'q' key.

## Customization

You can customize the following aspects of the code:

- Video input: Change the `video_path` variable to the path of your own video file.
- Model: You can replace the pre-trained machine learning model with your own model if needed.

## Credits

- MediaPipe: [https://mediapipe.dev/](https://mediapipe.dev/)
- OpenCV: [https://opencv.org/](https://opencv.org/)

## License

Feel free to use and modify this code for your own projects. If you have any questions or issues, please create a GitHub issue or contact [Mostafa Ameen](https://github.com/Mstf000).

Happy coding!

