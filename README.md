# AI_mouse.py
The detailed overview of my project.-------->

This Python script utilizes computer vision and hand tracking to create a virtual mouse control system. The project uses the OpenCV and MediaPipe libraries to detect hand landmarks in real-time from the webcam feed. By tracking specific landmarks on the hand, such as the index and thumb fingers, the script maps their positions to control the mouse cursor on the screen.

The hand landmarks are identified, and their coordinates are used to determine mouse actions. When the thumb is close to the index finger, a click action is simulated using PyAutoGUI. Additionally, if the distance between the thumb and index finger is within a certain range, the script moves the mouse cursor accordingly.

Overall, this project demonstrates a basic implementation of a virtual mouse control system using hand gestures.
