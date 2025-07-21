# Real-time Emotion Detection using DeepFace 😢😠😄

This project demonstrates a real-time emotion detection application using the DeepFace library with OpenCV and Python. It utilizes your webcam to detect faces, analyze the dominant emotion on each detected face, and display the results live.

## Key Features ✨
- Real-time Face Detection: Employs OpenCV's haarcascade_frontalface_default.xml for fast face detection.

- Emotion Analysis: Leverages DeepFace's robust models to identify dominant emotions (e.g., angry, disgust, fear, happy, sad, surprise, neutral).

- Visual Overlay: Displays bounding boxes around detected faces and labels them with the predicted emotion.

---

## Prerequisites 📋

Ensure you have Python installed (Python 3.8 - 3.12 is recommended).

```bash
python --version
```

---

## Installation 💻
#### 1. Clone this repository (optional, if you haven't already):

```bash
git clone https://github.com/satyaabdul/EmotionRecognition-Deepface.git
cd EmotionRecognition-Deepface
```

#### 2. Create a Virtual Environment (Highly Recommended):
Virtual environments help isolate your project's dependencies.

```bash
python -m venv venv
```

#### 3. Activate the Virtual Environment:

- Windows:
```bash
.\venv\Scripts\activate
```

- macOS / Linux:

```bash
source venv/bin/activate
```

Once activated, you'll see `(venv)` at the beginning of your terminal prompt.

#### 4. Install Dependencies:
Install the necessary libraries using pip. This will install `opencv-python` and `deepface`.

```bash
pip install opencv-python deepface
```

Note: DeepFace will automatically install its dependencies like TensorFlow/Keras. If you encounter issues with TensorFlow or Keras, ensure your Python version is compatible, or follow any advice given by your terminal.

---

## How to Run 🚀
Ensure your virtual environment is active (refer to step 3 in the Installation section).

#### Run the Python script:
```bash
python emotion.py
```

#### Stop the Application:
Press the `q` key on your keyboard when the video display window is active to stop the application.

---

## Code Structure 📁
- `emotion.py`: The main Python script containing the real-time emotion detection logic.

- `haarcascade_frontalface_default.xml`: (Typically installed with OpenCV, no manual download needed) The Haar Cascade model file for face detection.
