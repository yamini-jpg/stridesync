# Face Detection using OpenCV & Python

## 🚀 Overview
This project implements **face detection** using OpenCV in Python. It detects faces in images and real-time video streams using Haar Cascades or deep learning-based models.

## 🖼️ Demo
![Face Detection Demo](https://via.placeholder.com/600x300.png?text=Demo+Image)

## 📌 Features
- Detects faces in **images and videos**
- Uses **Haar Cascades / DNN-based models**
- Supports **real-time face detection** via webcam
- Works on **multiple faces** in a single frame
- Easily customizable for further enhancements (e.g., emotion detection, age estimation)

## 🛠️ Tech Stack
- **Python**
- **OpenCV**
- **NumPy**

## 📂 Project Structure
```
Face-Detection/
│── data/                 # Sample images
│── models/               # Pretrained models (Haar cascade, DNN)
│── face_detection.py     # Main face detection script
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
```

## 🔧 Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/Shankar2442/Face-Detection.git
   cd Face-Detection
   ```

2. **Create a virtual environment (optional but recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

## 🚀 Usage
### **Detect faces in an image**
```sh
python face_detection.py --image sample.jpg
```

### **Real-time face detection via webcam**
```sh
python face_detection.py --webcam
```

## ⚡ Example Output
✅ **Input Image:**

![Input](https://via.placeholder.com/300x200.png?text=Input+Image)

✅ **Detected Faces:**

![Output](https://via.placeholder.com/300x200.png?text=Detected+Faces)




