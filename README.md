# 🎯 YOLO AI Object Detection

## 📌 Project Overview
YOLO AI Object Detection is a real-time computer vision project developed using Python, OpenCV, and the Ultralytics YOLOv8 model. The application uses a webcam to detect and recognize multiple objects such as people, bottles, chairs, laptops, mobile phones, and many other common objects in real time.

This project demonstrates the use of Artificial Intelligence and Deep Learning for object detection and can be used as a beginner-friendly computer vision application.

---

## 🚀 Features

- Real-time object detection using webcam
- Detects multiple objects simultaneously
- Displays bounding boxes and class labels
- Uses the pre-trained YOLOv8 Nano model
- Fast and lightweight implementation
- Easy to understand and modify

---

## 🛠 Technologies Used

- Python 3
- OpenCV
- Ultralytics YOLOv8

---

## 📁 Project Structure

```
YOLO_Object_Detection/
│── detect.py
│── requirements.txt
│── README.md
```

---

## 📦 Installation

### Clone or Download the Project

Download the project folder or clone the repository.

### Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install ultralytics opencv-python
```

---

## ▶️ Running the Project

Run the following command:

```bash
python detect.py
```

The first time you run the project, YOLO automatically downloads the **yolov8n.pt** model. After that, the model is stored locally and future runs start immediately.

---

## 💻 How It Works

1. Opens the webcam.
2. Captures video frames in real time.
3. YOLOv8 processes each frame.
4. Detects objects present in the frame.
5. Draws bounding boxes and labels around detected objects.
6. Displays the processed video.
7. Press **Q** to exit the application.

---

## 🎯 Objects That Can Be Detected

Examples include:

- Person
- Bottle
- Chair
- Laptop
- Cell Phone
- Keyboard
- Mouse
- Book
- Backpack
- Car
- Bicycle
- Bus
- Dog
- Cat

and many more objects from the COCO dataset.

---

## 📷 Example Output

```
person 0.96
laptop 0.91
cell phone 0.88
chair 0.93
```

The detected objects are displayed with bounding boxes and confidence scores.

---

## 📚 Requirements

- Python 3.9 or later
- Webcam
- Internet connection (only for the first model download)

---

## 🔮 Future Improvements

- Object counting
- Multiple object tracking
- Custom YOLO model training
- Face detection integration
- Video file detection
- Save detection results
- GUI application using Tkinter or PyQt

---

## 👨‍💻 Author

Muhammad Aman Fasihe

BS Artifical Intelligence

CodeAlpha Internship2026

---

## 📄 License

This project is intended for educational and learning purposes.