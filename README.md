# 🖐️  Hand Gesture Paint App

## Overview
The **Hand Gesture Paint App** is an interactive application that allows users to draw on a virtual canvas using hand gestures detected via a webcam. The app utilizes **OpenCV, MediaPipe, and Streamlit** to create an intuitive and touchless drawing experience.

## Features
- Hand gesture recognition for drawing.
- Different colors for drawing: **Blue, Green, Red, Yellow**.
- Clear button to erase the canvas.
- Real-time webcam feed with hand tracking.
- Built with **Streamlit** for an easy-to-use interface.

## Installation
To run this project, you need to install the required dependencies. You can do so using the following command:

```bash
pip install opencv-python numpy mediapipe streamlit
```

## Usage
Run the application using the command:

```bash
streamlit run file_name.py
```

This will start the Streamlit server and open the application in your web browser.

## How It Works
1. The application initializes the webcam and detects hand landmarks using **MediaPipe**.
2. Users can use their index finger to draw on the virtual canvas.
3. If the thumb and index finger are close, the app registers a new stroke.
4. Color selection and the clear function can be accessed by hovering over designated areas.
5. The drawing is displayed in real-time using OpenCV and updated in the Streamlit app.

## Controls
- Move your index finger to draw.
- Use the top menu to select different colors.
- Hover over the **CLEAR** button to erase the drawing.
- Press 'q' on your keyboard to exit the application.

## Dependencies
- OpenCV
- NumPy
- MediaPipe
- Streamlit

## Future Enhancements
- Add more gesture-based controls.
- Implement multi-hand support.
- Save the drawings as images.

## Author
This project was developed by Salman Ahmed. Feel free to contribute or suggest improvements!



