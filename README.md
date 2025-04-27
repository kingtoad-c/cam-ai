# 🧠🕸️ VisionWeaver: Real-Time Face Mesh, Age Prediction & Object Detection 🎯

![object_detector](https://github.com/user-attachments/assets/2f939f57-ad28-4e8c-917a-bb1a88c75315)


*Weave reality into code — see faces, predict ages, detect the world.*

---

## 📜 Description

**VisionWeaver** is an intelligent real-time computer vision system that:
- Builds **smart green facial meshes** with facial landmarks (avoiding eyes).
- Predicts **estimated ages** and displays them above detected faces.
- Detects and identifies **over 80 different real-world objects** — fast and lightweight.

Built fully using **OpenCV**, **Dlib**, and simple lightweight models.  
⚡ **No TensorFlow, no heavy frameworks, no API keys needed!** ⚡

---

## 🚀 Features

- 🕸️ **Facial Web Mapping**: Draws beautiful green triangle meshes across key facial features
- 🎯 **Real-Time Object Detection**: Detects **80+ different object types** (COCO classes)
- 🧓 **Age Prediction**: Predicts the estimated age and displays it above each face
- 🛡️ **Lightweight and Fast**: Runs on laptops without dedicated GPUs
- 🎥 **Webcam Ready**: Instant live video feed capture
- 🛠️ **Fully Offline**: No Internet connection needed after downloading

---

## 📦 Object Classes Detected

This project detects **over 80 classes**, including:

| People | Vehicles | Furniture | Animals | Electronics | Misc |
|:------:|:--------:|:---------:|:-------:|:-----------:|:----:|
| Person | Car | Chair | Dog | Laptop | Bottle |
| Bicycle | Truck | Couch | Cat | Cell Phone | Cup |
| Motorcycle | Boat | Bed | Horse | TV Monitor | Fork |
| Airplane | Bus | Dining Table | Sheep | Mouse | Knife |
| Train | Traffic Light | Toilet | Cow | Keyboard | Spoon |
| ... | ... | ... | ... | ... | ... |

*(Full COCO-SSD object list supported.)*

---

## 📥 Download

All files needed are packed and ready:  
👉 [**Click here to Download VisionWeaver**](https://drive.google.com/file/d/1r0LhiuuqOjDQd34q3g7I9WlrvQ6reLUY/view?usp=sharing)

✅ Included in the ZIP:
- `run.bat`
- `main.py`
- `shape_predictor_68_face_landmarks.dat`
- `age_deploy.prototxt`
- `age_net.caffemodel`
- Object detection models
- Optional sample images

---

## ⚙️ Installation

Install required libraries:

```
pip install opencv-python dlib numpy

```

# ▶ Run

To run the program just run the file:
- `run.bat`

or if on Linux:
```
python main.py
```


