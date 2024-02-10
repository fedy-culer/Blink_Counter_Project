# Blink_Counter_Project

The `BlinkCounter.py` script captures video frames from a video file and detects faces using the `FaceMeshDetector` module from the `cvzone` library. It calculates the ratio of vertical eye distance to horizontal eye distance to determine whether a blink has occurred. Additionally, it displays a live plot of the blink ratio over time and counts the number of blinks detected.

## Usage

Upon execution, the script will open a window displaying the video feed along with a plot showing the blink ratio over time. It will also show a counter indicating the number of blinks detected.


## Dependencies

The script requires the following Python libraries:

- `cv2` (OpenCV)
- `cvzone` (Custom computer vision library)

## Notes

- Ensure that you have a video file named "White Guy Blinking Meme.mkv" in the same directory as the script, or modify the script to use a different video file by changing the `VideoCapture` path.
- The script detects blinks based on the ratio of vertical eye distance to horizontal eye distance. Adjust the blink ratio threshold (`34.5` in the script) as needed based on your application.
- The blink counter increments each time a blink is detected. You can adjust the sensitivity of blink detection by modifying the blink counter logic in the script.

That's it! You should now be able to detect blinks and monitor the blink ratio in real-time using the `BlinkCounter.py` script.
