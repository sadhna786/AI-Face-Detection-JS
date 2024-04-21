# AI-Face-Detection-JS

# Real-Time Face Detection with AI

This project enables real-time face detection through a webcam using AI technology. It utilizes the Face API JS library built on TensorFlow to achieve accurate and efficient face detection.

# Important Updates

Deprecated API Replacement
navigator.getUserMedia: Replaced all instances of navigator.getUserMedia with navigator.mediaDevices.getUserMedia, as the former is now deprecated.
Low-End Devices Bug Fix
Video Event Listener: Replaced the video event listener for play with the playing event to ensure that it fires up only when the media has enough data to start playing. This addresses issues on low-end machines where errors would arise from the Face API due to premature firing of the event.

# Usage

Open the application in a supported web browser.
Allow access to the webcam when prompted.
Experience real-time face detection and visualization of faces and expressions in the video stream.

# Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please submit a pull request or open an issue on GitHub.
