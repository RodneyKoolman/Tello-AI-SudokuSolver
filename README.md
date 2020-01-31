# Tello AI Sudoku Solver
Use this project to fly a DJI Ryze Tello autonomously and solve Sudoku puzzles in the air using Python, TensorFlow, Keras and OpenCV.

Prerequisites:
- DJI Ryze Tello: https://store.dji.com/product/tello
- Nvidia Jetson Nano (optional): https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano-developer-kit/
- Wifi dongle (optional, but a Wifi connection to the drone is necessary)

I am using a Nvidia Jetson Nano (Ubuntu) to run the code and control the Tello. You can use every computer to run this code, although the Machine Learning part and Hough transform algorithm are a little heavy, so you should use it with a good CPU/GPU. Don't expect 30 FPS. On a Jetson Nano via the drone's stream i am able to get around 20 FPS, and when the algoritm detects a Sudoku grid it will drop to 3/4 FPS. But it is usable :).
