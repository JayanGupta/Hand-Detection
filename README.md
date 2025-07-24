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

## Notebooks

This repository also includes a couple of Jupyter notebooks where I’ve explored some basic computer vision concepts using OpenCV:

- `Haar_Cascades.ipynb`: Simple face detection using Haar cascades.
- `RGB.ipynb`: Basic operations and color channel manipulation with OpenCV.

These notebooks are included to reflect my ongoing practice and understanding of core computer vision tools in Python.

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
