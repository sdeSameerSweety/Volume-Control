# Hand Gesture Controlled Volume 

This Python script allows you to control the system's volume using hand gestures captured from your webcam. It utilizes the MediaPipe library for hand tracking and the Pycaw library to adjust the system's master volume based on the detected gestures.

### Prerequisites:
- Python 3.x installed
- OpenCV library (`cv2`)
- Mediapipe library (`mediapipe`)
- NumPy library (`numpy`)
- comtypes library (`comtypes`)
- pycaw library (`pycaw`)

### Instructions:
1. Install the required libraries if you haven't already. You can use `pip install opencv-python mediapipe numpy comtypes pycaw` to install them.
2. Run the provided Python script on your machine.
3. Position your hand in front of the webcam and adjust the distance between two fingers to control the volume.

### Script Overview:
- The script captures video frames from the webcam.
- It detects hand landmarks using the MediaPipe library.
- Calculates the distance between two specific landmarks to determine the volume control gesture.
- Maps the hand gesture length to the volume range and adjusts the system volume accordingly.
- Displays the camera feed with hand landmarks and gestures annotated in real-time.

### Usage:
- Use the distance between two fingers to increase or decrease the volume.
- Close the program by pressing the 'q' key.

Enjoy controlling your system's volume with hand gestures! 🖐️🔊