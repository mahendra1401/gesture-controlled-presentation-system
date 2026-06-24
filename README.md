# gesture-controlled-presentation-system
AI-powered gesture-controlled presentation system built using Python, OpenCV, MediaPipe, and PyAutoGUI.
# AI Gesture Controlled Presentation System

## Project Overview
This project enables users to control presentation slides using hand gestures captured through a webcam.

Developed as part of an AI and Computer Vision Bootcamp to learn gesture recognition, hand tracking, and automation using Python.

## Technologies Used
- Python
- OpenCV
- MediaPipe
- PyAutoGUI

## Features
- Open Palm → Next Slide
- Three Fingers → Previous Slide
- Two Fingers → Start Slideshow
- Fist → Exit Slideshow

## How It Works
1. Captures webcam video.
2. Detects hand landmarks using MediaPipe.
3. Recognizes gestures based on finger positions.
4. Maps gestures to slide controls.
5. Uses PyAutoGUI to automate keyboard actions.

## Installation and Execution

### Prerequisites

* Python 3.9 or above
* Webcam
* Internet connection (for first-time model download)

### Step 1: Clone the Repository

```bash
git clone https://github.com/mahendra1401/gesture-controlled-presentation-system.git
cd gesture-controlled-presentation-system
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Download the MediaPipe Model

```bash
python setup_models.py
```

### Step 4: Run the Application

```bash
python main.py
```

### Step 5: Use the Gestures

| Gesture       | Action          |
| ------------- | --------------- |
| Open Palm     | Next Slide      |
| Three Fingers | Previous Slide  |
| Two Fingers   | Start Slideshow |
| Fist          | Exit Slideshow  |

### Exit Application

Press:

```text
q
```

in the webcam window to close the application.

## Learning Outcomes
- Computer Vision
- Gesture Recognition
- Human-Computer Interaction
- Python Automation
