
# Real-time Face Verification

This Python script performs real-time face verification using a webcam feed. It leverages OpenCV for video capture and the DeepFace library for face verification.

## Prerequisites

- Python 3.8 or higher
- Required libraries: `opencv-python`, `deepface`

## Installation

To install the required libraries, run the following commands:

```bash
pip install opencv-python deepface
```

## Usage

1. **Prepare a Reference Image:**

   Ensure you have a reference image named `reference2.jpg` in the same directory as `main.py`. This image will be used for face verification.

2. **Run the Script:**

   Start the face verification script with the following command:

   ```bash
   python main.py
   ```

3. **Interact with the Script:**

   The script will start capturing video from your webcam. It will check for a face match every 60 frames and display "MATCH!" if a face match is found, or "NO MATCH!" otherwise. Press `q` to quit the script.

## Source

This script is based on a tutorial from YouTube: [Real-time Face Recognition with Python and OpenCV](https://www.youtube.com/watch?v=pQvkoaevVMk&ab_channel=NeuralNine)

## Example Interaction

1. Start the script:
   ```
   $ python main.py
   ```

2. Observe the video feed and the face match status.

Feel free to modify the script to fit your needs.
