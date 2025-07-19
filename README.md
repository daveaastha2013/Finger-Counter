# Finger-Counter
A real-time finger counting system built using **OpenCV, Python and Mediapipe**. The project uses a webcam feed to detect a hand and count the number of fingers raised, displaying the output on the screen.
## Features
- Real-time hand detection using webcam
- Counts number of raised fingers accurately
- Visualizes hand landmarks and count
- Lightweight and easy to run on most systems

## How it works
- The webcam captures video in real time.
- The frame is passed through MediaPipe’s Hand Tracking solution.
- Landmarks are analyzed to determine which fingers are raised.
- The number of fingers raised is displayed on screen.
The demo for the same has been attached

## How to run
```
# Clone the repo
git clone https://github.com/daveaastha2013/finger_counter
cd finger_counter

# Install dependencies
pip install -r requirements.txt

# Run the code
python main.py
```
## Future Improvements
- Add gesture recognition (e.g., thumbs up, okay symbol)
- Support multiple hands
- Integrate with games or robot control
