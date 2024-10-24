# Eye Controlled Mouse

## Description

The **Eye Controlled Mouse** project enables users to control their computer’s mouse pointer using their eye movements, leveraging computer vision and facial landmarks detection techniques. This Python-based project uses `OpenCV` for camera feed processing, `MediaPipe` for face and eye landmark detection, and `PyAutoGUI` to interact with the screen. The main aim is to provide an accessible and hands-free interface for controlling the mouse, offering potential benefits for users with physical disabilities or those looking for alternative input methods.

## Features
- Tracks eye movements to control the mouse cursor.
- Detects blinking to simulate mouse clicks.
- Uses facial landmark detection with refined eye tracking.
- Real-time video processing and responsive interaction.

## Technologies Used
- **OpenCV**: For real-time video capture and image processing.
- **MediaPipe**: For detecting facial landmarks and refining eye movements.
- **PyAutoGUI**: For simulating mouse pointer movements and clicks.
  
## Setup Instructions
### Prerequisites
Ensure you have Python 3.x installed along with the following libraries:
- `opencv-python`
- `mediapipe`
- `pyautogui`

You can install the dependencies via pip:

```bash
pip install opencv-python mediapipe pyautogui
```

### Running the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/eye-controlled-mouse.git
   ```
2. Navigate to the project folder:
   ```bash
   cd eye-controlled-mouse
   ```
3. Run the script:
   ```bash
   python eye_controlled_mouse.py
   ```

The camera will open, and the system will start tracking your eye movements to control the mouse cursor. Blinking will trigger mouse clicks.

## Usage
- Move your eyes to control the pointer.
- A small green circle will indicate the points being tracked for the eye.
- Blink to simulate a mouse click (detected by comparing the vertical distances of specific facial landmarks).
  
## Project Structure
- `eye_controlled_mouse.py`: Main script that runs the program.
- `requirements.txt`: Contains the list of required Python libraries (optional).

## Future Improvements
- Add support for both eyes to enhance precision.
- Improve the click detection to avoid false positives.
- Implement scroll functionality through eye gestures.
  
## Contributing
Feel free to fork this repository and contribute by submitting pull requests. Ensure that you maintain the coding style and provide appropriate documentation for any new feature or bug fix.
