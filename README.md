# Face Touch Detector

Detect and analyze face-touch events in videos using PyTorch and MediaPipe.

---

##  Project Overview

Touching your face is a common unconscious habit, but it can increase the risk of infection (germs, colds, COVID-19).  
This project automatically detects when you (or a subject) touch your face in a video, using a combination of deep learning (PyTorch for face detection) and real-time hand landmark detection (MediaPipe).

---

## Features

- **Face detection** in each frame using a PyTorch MTCNN model.
- **Hand and fingertip detection** using Google’s MediaPipe.
- **Automatic detection of “face touch” events:** logs frame, finger, and location.
- **Visual overlays**: bounding boxes and fingertip highlights.
- **Exportable CSV of all detected touches** for further analysis.


---

##  Technologies Used

- **PyTorch** (`facenet-pytorch`) – face detection
- **MediaPipe** – hand and fingertip detection
- **OpenCV** – video reading and drawing
- **Google Colab** – easy, no-install workflow (works with video uploads)
- **Python** (3.x)

---

## How to Use

1. **Clone this repo** (or open the included Colab notebook in Google Colab).
2. **Upload a video** of yourself (or a subject) touching their face.
3. **Run all notebook cells**:
    - Detects faces and fingertips frame-by-frame.
    - Logs and visualizes all “face touch” events.
    - Exports a `.csv` with each touch event’s details.
4. **Analyze the results** or download the annotated video.

---

##  Example Output

- Annotated video frames with green boxes (face), blue/yellow circles (fingertips/touches).

---

##  Key Learnings & Challenges

- Integrated two state-of-the-art computer vision frameworks (PyTorch and MediaPipe).
- Built a reproducible video analysis pipeline in Python/Colab.
- Tackled common issues in computer vision: occlusion, landmark drift, and working with real-world, noisy video data.
- Explored practical applications (habit tracking, health, behavioral research).

---

##  Possible Extensions

- **Real-time webcam monitoring**
- **Multi-person detection**
- **Alert system for repeated touching**
- **Improved touch event filtering (debouncing)**
- **Deploy as a simple web app**

---

## Credits

- [facenet-pytorch](https://github.com/timesler/facenet-pytorch)
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- Google Colab

---

## 📧 Contact
Plamena Naydenova, PhD, Msc, Bsc
Data scientist| www.linkedin.com/in/plamena-naydenova
Questions or want to collaborate?  
Get in touch!
