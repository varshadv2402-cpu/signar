# SignAR — Virtual Classroom Assistant for Deaf Students

A CNN-based sign-language recognition system that translates gestures into text in real time, built to improve classroom accessibility for deaf students.

## Overview
SignAR enables real-time classroom interaction for deaf students by recognizing sign-language gestures via computer vision and converting them into text, reducing communication barriers in live learning environments.

## Approach
- Built a CNN-based recognition model to classify sign-language gestures from video input
- Used OpenCV for real-time video capture and preprocessing
- Trained and evaluated the model using TensorFlow
- Measured performance using F1 score and Precision to ensure reliable real-world recognition

## Tech Stack
- **Language:** Python
- **Computer Vision:** OpenCV
- **Deep Learning:** TensorFlow
- **Evaluation Metrics:** F1 Score, Precision

## Getting Started
```bash
git clone <your-repo-url>
cd signar
pip install -r requirements.txt
python app.py
```
*(Update the commands above to match your actual file structure once uploaded.)*

## Impact
Designed to support real-time, in-classroom interaction so deaf students can follow along without needing a dedicated human interpreter present at all times.

## Future Improvements
- Expand gesture vocabulary coverage
- Add two-way translation (text/speech back into sign language)
- Optimize for lower-latency, on-device inference
