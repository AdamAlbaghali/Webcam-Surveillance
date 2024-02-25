# Webcam Video Surveillance with OpenCV

This Python script provides a simple implementation of video surveillance using a webcam and OpenCV library. It detects faces and bodies in the video stream and records video clips when activity is detected. The recording stops after a certain duration of inactivity.

## Requirements
- Python 3.x
- OpenCV library (`cv2`)
- Haar cascade classifiers for face and body detection

## Installation
1. Clone this repository to your local machine using the following command:
    ```
    git clone https://github.com/AdamAlbaghali/Webcam-Surveillance.git
    ```

2. Navigate to the directory containing the script:
    ```
    cd your-repository
    ```

3. Install the required Python packages:
    ```
    pip install -r requirements.txt
    ```

4. Download the Haar cascade XML files for face and body detection and place them in the same directory as the script.

## Usage
1. Run the script using a Python interpreter:
    ```
    python surveillance.py
    ```

2. Ensure that your webcam is properly connected and configured on your system.

3. The script will start capturing video from the webcam and display it in a window named "Camera".

4. When faces or bodies are detected in the video stream, the script will start recording video clips.

5. The recording will stop automatically after a specified duration of no detection.

6. Press the 'q' key to exit the script and stop video capture.

7. The recorded video clips will be saved in the same directory as the script.

## Customization
- You can adjust the detection parameters (`scaleFactor`, `minNeighbors`, etc.) in the script for better performance.
- Modify the `SECONDS_TO_RECORD_AFTER_DETECTION` variable to change the duration of video recording after detection.
- Customize the file format and output directory for recorded video clips in the script.

## Note
- Make sure to download the required Haar cascade XML files and update the file paths accordingly in the script.
- You may need to grant permissions for accessing the webcam on your system.

