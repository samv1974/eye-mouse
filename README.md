# Eye-Controlled Mouse

This project utilizes computer vision techniques to control the mouse pointer using eye movements. It employs the Mediapipe library for facial landmark detection and PyAutoGUI for mouse control.

## Prerequisites

Before running the code, make sure you have the following installed:

- Python 3.x
- OpenCV
- Mediapipe
- PyAutoGUI

Install the required libraries using:

```bash
pip install opencv-python mediapipe pyautogui
```
## Usage

1. **Run the `main.py` script:**

    ```bash
    python main.py
    ```

2. The application will use your computer's webcam to track your facial landmarks.

3. Move your eyes to control the mouse pointer.

4. Blinking both eyes simultaneously can be used as a click action.

## Dependencies

- **OpenCV:** [https://opencv.org/](https://opencv.org/)
- **Mediapipe:** [https://mediapipe.dev/](https://mediapipe.dev/)
- **PyAutoGUI:** [https://pyautogui.readthedocs.io/](https://pyautogui.readthedocs.io/)

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to the contributors of OpenCV, Mediapipe, and PyAutoGUI for their amazing libraries.

