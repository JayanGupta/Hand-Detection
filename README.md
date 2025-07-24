# Hand Recognition System

This project builds a hand recognition model using computer vision techniques to detect and track hand gestures in real-time. The system detects the number of fingers raised and whether the thumb is up, providing useful information for gesture-based applications.

## Project Overview

The Hand Recognition System uses a webcam feed to capture images and detect hand landmarks using the **MediaPipe** library. The model processes these landmarks to count the number of fingers raised and check if the thumb is up, displaying the results in real-time.

## Features

* Real-time hand detection and tracking using MediaPipe.
* Detection of up to two hands with finger counting.
* Thumb detection to identify if the thumb is raised.
* Visual representation of hand landmarks on the webcam feed.
* Outputs the number of fingers raised and whether the thumb is up.

## Libraries Used

* **cvzone**: For hand tracking and finger counting.
* **MediaPipe**: For detecting hand landmarks and connections.
* **OpenCV**: For capturing and processing the webcam feed.
* **PIL (Pillow)**: For image manipulation and conversion.

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/hand-recognition.git
cd hand-recognition
```

Install the required dependencies:

```bash
pip install cvzone mediapipe opencv-python
```

## How It Works

1. **Capture Image from Webcam**: The system captures a frame from the webcam using JavaScript and Python integration.
2. **Process Image**: The captured frame is passed through the MediaPipe hand detection model to identify hand landmarks.
3. **Count Fingers and Detect Thumb**: Using the detected landmarks, the number of raised fingers is counted, and the system checks if the thumb is raised.
4. **Display Results**: The results are displayed on the webcam feed, showing the hand landmarks and the count of fingers and thumb status.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hand-recognition.git
   cd hand-recognition
   ```

2. Run the Python script:

   ```bash
   python hand_recognition.py
   ```

3. When the script is running, place your hand in front of the webcam. The system will process the image, count the raised fingers, and detect whether the thumb is up, displaying this information on the screen.

## Code Breakdown

### Libraries Used

* **OpenCV**: For capturing video feed and processing images.
* **cvzone**: For hand tracking and gesture recognition.
* **MediaPipe**: For detecting hand landmarks and drawing connections.
* **PIL (Pillow)**: For handling image data and base64 encoding/decoding.

### Main Functions

* **capture\_frame()**: Captures an image from the webcam and returns it as an array.
* **count\_fingers()**: Counts the number of fingers raised based on hand landmarks.
* **detect\_thumb()**: Detects if the thumb is raised using the landmarks of the hand.

### Example Output

The following output is displayed on the webcam feed:

* The hand landmarks are drawn in real-time.
* The number of raised fingers is displayed at the top of the feed.
* If the thumb is raised, a message indicating "Thumb: 1" will be displayed.

---
