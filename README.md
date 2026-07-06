# 🎯 Real-Time Object Detection using YOLOv3

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)
![YOLOv3](https://img.shields.io/badge/YOLO-v3-red)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-AI-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📌 Project Overview

This project implements a **Real-Time Object Detection System** using the **YOLOv3 (You Only Look Once)** deep learning model and **OpenCV**. The application detects multiple objects from live webcam streams and static images with high accuracy while displaying bounding boxes, object labels, confidence scores, and object counts.

The project also provides an interactive **Tkinter GUI**, allowing users to easily start and stop object detection.

---

## 🚀 Features

- 🎥 Real-time webcam object detection
- 🖼️ Object detection on images
- 📦 Detects 80+ object classes using COCO dataset
- 🏷️ Displays bounding boxes with object labels
- 📊 Shows confidence scores
- 🔢 Counts detected objects
- ⚡ Supports GPU acceleration using CUDA (if available)
- 🖥️ Simple and user-friendly Tkinter GUI
- 📷 Supports live camera feed

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| OpenCV | Computer Vision |
| YOLOv3 | Object Detection Model |
| NumPy | Numerical Computing |
| Pillow | Image Processing |
| Tkinter | GUI Development |
| Matplotlib | Image Visualization |
| COCO Dataset | Pre-trained Object Classes |

---

## 📂 Project Structure

```
Real-Time-Object-Detection/
│
├── src/
│   ├── realtime_detection.py
│   └── image_detection.py
│
├── models/
│   ├── yolov3.cfg
│   ├── coco.names
│   └── yolov3.weights
│
├── images/
│   ├── home.png
│   ├── detection.png
│   ├── output.png
│   └── architecture.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Uttam007-esc/Real-Time-Object-Detection-.git
```

```bash
cd Real-Time-Object-Detection-
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 📥 Download YOLOv3 Weights

Download the **yolov3.weights** file from the official YOLO website:

https://pjreddie.com/media/files/yolov3.weights

After downloading, place the file inside the **models/** folder.

```
models/
    yolov3.cfg
    coco.names
    yolov3.weights
```

---

## ▶️ Run the Project

### Real-Time Webcam Detection

```bash
python src/realtime_detection.py
```

### Image Detection

```bash
python src/image_detection.py
```

---

## 🔄 Project Workflow

```
Input Image / Webcam
          │
          ▼
      OpenCV
          │
          ▼
    YOLOv3 Network
          │
          ▼
 Feature Extraction
          │
          ▼
 Object Detection
          │
          ▼
 Non-Maximum Suppression
          │
          ▼
 Bounding Boxes & Labels
          │
          ▼
 Display Output
```

---

## 📊 Results

The system detects multiple objects in real-time and displays:

- Object Name
- Bounding Box
- Confidence Score
- Total Object Count

Example output:

- Person
- Bottle
- Chair
- Laptop
- Cell Phone
- Car
- Bus

---

## 💡 Applications

- Smart Surveillance Systems
- Autonomous Vehicles
- Traffic Monitoring
- Security Systems
- Robotics
- Smart Cities
- Industrial Automation
- Retail Analytics

---

## 🔮 Future Enhancements

- Upgrade to YOLOv8
- Object Tracking
- Face Recognition
- Custom Dataset Training
- TensorRT Optimization
- Mobile Application Support
- Edge AI Deployment

---

## 📈 Skills Demonstrated

- Computer Vision
- Deep Learning
- Object Detection
- Image Processing
- Python Programming
- OpenCV
- GUI Development
- Machine Learning
- AI Application Development

---

## 👨‍💻 Author

### Uttam Kumar Dingari

🎓 B.Tech – Data Science

🔗 GitHub: https://github.com/Uttam007-esc

🔗 LinkedIn: https://www.linkedin.com/in/uttamkumardingari/

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It motivates me to build more AI and Machine Learning projects.

---

## 📜 License

This project is licensed under the MIT License.
