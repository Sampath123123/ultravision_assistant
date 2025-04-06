Here's a shortened version of the README:

---

# Personal Desktop Assistant - AI

A voice-activated AI assistant that performs tasks like object detection, web search, and opening applications.

## Features

- **Voice Commands**: Interact using your microphone.
- **Object Detection**: Detect objects via the camera using YOLOv8.
- **Web Search**: Search Google, YouTube, Wikipedia.
- **App Controls**: Open Camera, Calculator, and more.
- **Text-to-Speech**: AI speaks back to you.

## Requirements

Install dependencies:

```bash
pip install pyautogui speech_recognition pyttsx3 win32com.client google-generativeai gtts playsound opencv-python ultralytics streamlit
```

Download YOLOv8 model weights (`yolov8n.pt`).

Create a `config.py` file with your Google API key:

```python
GENAI_API_KEY = "YOUR_GOOGLE_GENERATIVE_API_KEY"
```

## Running the Project

1. Clone the repo.
2. Run the Streamlit app:

```bash
streamlit run assistant.py
```

## Commands

- **"Open Camera"**: Opens the camera.
- **"Open Calculator"**: Opens the calculator.
- **"Take Screenshot"**: Takes a screenshot.
- **"Open Music"**: Plays a predefined music file.
- **"The Time"**: Tells the current time.
- **"Go Offline"**: Shuts down the assistant.

### Web Search

- **"Search [query] in Google"**
- **"Search [query] in Wikipedia"**
- **"Search [query] in YouTube"**

### Object Detection

- **"Detect Objects"**
- **"See Objects"**
- **"What objects detected"**

## Developed By

- **G. Sampath**
- GitHub: [G. Sampath's GitHub](https://github.com/sampath123123)
- LinkedIn: [G. Sampath's LinkedIn](https://www.linkedin.com/in/gugulothu-sampath-829b33299)

---

This version is more concise while still covering the key points.
