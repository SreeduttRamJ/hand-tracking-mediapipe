# Hand Tracking using MediaPipe

![Hand Tracking Demo](demo.gif)

## Overview

This project showcases hand tracking using the MediaPipe library in Python combined with OpenCV. It enables real-time hand detection and tracking from a webcam feed, providing visual feedback by overlaying the detected hand positions and indicating their handedness (left or right).

## Features

- **Real-time Hand Tracking**: The script captures video from your webcam and utilizes the power of MediaPipe to identify and track hands.

- **Handedness Detection**: It displays whether the detected hands are "Both Hands," "Left Hand," or "Right Hand."

- **Configuration Options**: The script allows you to configure various parameters such as model complexity, detection and tracking confidence thresholds, and the maximum number of hands to detect.

- **User-Friendly Interface**: The user interface is straightforward and easy to use, making it a great starting point for projects that involve hand gesture recognition, sign language translation, or any application that requires hand tracking.

## Getting Started

Follow these steps to get started with the project:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/hand-tracking-mediapipe.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hand-tracking-mediapipe/code
   ```

3. Run the script:

   ```bash
   python hand_tracking.py
   ```

4. Enjoy the real-time hand tracking experience! The script will display the webcam feed with hand tracking overlays.

5. To exit the program, simply press 'q' in the webcam feed window.

## Configuration

You have the flexibility to adjust various parameters in the script:

- `static_image_mode`: Set to `True` for static images or `False` for webcam feed.
- `model_complexity`: Choose the model complexity (0, 1, or 2) to balance speed and accuracy.
- `min_detection_confidence`: Set the minimum confidence threshold for hand detection.
- `min_tracking_confidence`: Set the minimum confidence threshold for hand tracking.
- `max_num_hands`: Define the maximum number of hands to detect (default is 2).

## Contributing

Contributions are welcome! If you have any enhancements, bug fixes, or feature suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project is made possible by the fantastic work of the MediaPipe and OpenCV communities. We express our gratitude for their contributions to the field of computer vision.

---
