# 🖼️ Object Detection Using YOLOv8

## 📖 Overview
This project demonstrates **object detection** in videos using **YOLOv8** integrated with a **Flask web application**. Users can upload videos, and the system processes them to detect and highlight objects.

## 🚀 Features
- **YOLOv8 Integration**: Utilizes the YOLOv8 model for accurate object detection.
- **Flask Web Interface**: Provides a user-friendly web interface for video uploads and result viewing.
- **Video Processing**: Processes uploaded videos to detect objects and generates output videos with bounding boxes.

## 🏗️ Project Structure
```
Object-Detection-Using-YOLOv8-
├── static/
│   └── files/           # Directory for storing uploaded and processed video files
├── templates/
│   └── index.html       # HTML template for the Flask web interface
├── __pycache__/         # Cached Python files
├── YOLO_Video.py        # Script for processing videos using YOLOv8
├── flaskapp.py          # Main Flask application script
└── output.avi           # Sample output video demonstrating object detection
```

## 🛠️ Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/The-Symbol/Object-Detection-Using-YOLOv8-.git
   cd Object-Detection-Using-YOLOv8-
   ```

2. **Install Required Dependencies**:
   Ensure you have the following installed:
   - Python 3.x
   - Flask
   - OpenCV
   - YOLOv8 model files

   Install Python dependencies using pip:
   ```bash
   pip install flask opencv-python
   pip install cv2
   pip install ultralyitcs
   ```

3. **Download YOLOv8 Model**:
   - Obtain the YOLOv8 model weights from the official repository.
   - Place the model files in the appropriate directory accessible by `YOLO_Video.py`.

4. **Run the Flask Application**:
   ```bash
   python flaskapp.py
   ```
   Access the web interface by navigating to `http://127.0.0.1:5000/` in your browser.

## 🎬 Usage

- **Upload Video**: Use the web interface to upload a video file.
- **Process Video**: The system processes the uploaded video, detecting objects frame by frame.
- **Download Output**: Once processing is complete, download the output video with detected objects highlighted.

## 🤖 YOLOv8 Model

**YOLO (You Only Look Once)** is a state-of-the-art, real-time object detection system. YOLOv8 is the latest version, offering improved accuracy and speed. For more details, refer to the [Ultralytics YOLOv8 Repository](https://github.com/ultralytics/ultralytics).

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: Ensure compliance with the YOLOv8 model's licensing terms when using this project.*

