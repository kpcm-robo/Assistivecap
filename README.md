# Assistivecap
# Eye Controlled Mouse

This project enables you to control your mouse cursor using eye movements and simulate clicks by blinking.

## Dependencies

OpenCV (cv2): for image and video processing
MediaPipe: for face and facial landmark detection
PyAutoGUI: for controlling mouse and keyboard actions
## Installation

Install the required libraries:

Bash
pip install opencv-python mediapipe pyautogui
Use code with caution. Learn more
## Usage

Run the Python script:

Bash
python eye_controlled_mouse.py
Use code with caution. Learn more
Position your face within the webcam's view.

Move your eyes to control the mouse cursor.

Blink your left eye to simulate a mouse click.

## Key Features

Tracks eye movement using facial landmarks
Maps eye position to screen coordinates
Simulates mouse clicks with blink detection
## Troubleshooting

Ensure proper lighting: Good lighting is essential for accurate face and landmark detection.
Adjust webcam position: Find the optimal position for capturing your face clearly.
Calibrate eye movement sensitivity: If needed, fine-tune the sensitivity based on your individual eye movements.
## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
