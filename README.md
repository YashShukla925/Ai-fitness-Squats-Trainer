## Overview
This project is an AI-powered squat trainer that uses Google's MediaPipe framework to detect and analyze squat exercises in real-time. It provides feedback based on body posture to help users maintain proper squat form.

## Features
- **Real-time squat detection** using MediaPipe Pose
- **Feedback on posture correctness** to improve form
- **Repetitions counter** to track performance
- **Simple and efficient UI** for ease of use

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install mediapipe opencv-python numpy
```
## How it Works
- Pose Detection: MediaPipe Pose detects key landmarks such as hips, knees, and ankles
- Angle Calculation: Calculates joint angles to determine squat depth and form.

## Refer Images
![Screenshot 2025-01-24 230127](https://github.com/user-attachments/assets/b1b5bedb-ab28-4d06-9edc-5bec14b1930a)
![Screenshot 2025-01-24 230318](https://github.com/user-attachments/assets/aee391c3-8247-445b-8196-04fc49c31321)
![Screenshot 2025-01-24 230342](https://github.com/user-attachments/assets/41589dcb-304e-4ffd-ba95-e5b0343f58f9)
