# Python Gaze & Face Tracker

A small project that tracks face landmarks and gaze using MediaPipe and OpenCV.

This repository contains scripts to detect facial landmarks and estimate gaze direction. The primary entry point is `main.py`.

## Files of interest
- `main.py` — primary script to run the tracker.
- `AngleBuffer.py` — helper for storing/averaging angle values.
- `mediapipe_landmarks_test.py` — example/testing code for MediaPipe landmark detection.
- `test.py` — small test harness.

## Requirements
The project uses Python 3.8+ and depends on the packages listed in `requirements.txt`.

To install dependencies:

```bash
python -m pip install -r requirements.txt
```

If you prefer a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

## Running

Run the tracker with:

```bash
python main.py
```

If you only want to test MediaPipe landmarks output, run:

```bash
python mediapipe_landmarks_test.py
```

## Notes
- Ensure your webcam is connected and accessible by OpenCV.
- If you run into import or dependency issues, confirm the Python interpreter and virtual environment are correct.

## License
This project does not include a license file. Add one (for example, `MIT`) if you plan to publish or share the code.
# eye-gaze-face-tracker
