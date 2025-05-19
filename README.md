# Python-Object-Detector
A real-time object detection project using **YOLOv11** and Python. This tool allows you to detect objects in images or videos using a pretrained YOLOv11 model.


## 📁 Project Structure

```bash
Python-Object-Detector/
│
├── yolov11_detect.py          # Main detection script
├── yolov11_colab.ipynb        # (Optional) Colab notebook
├── requirements.txt           # List of dependencies
├── weights/                   # Pretrained YOLOv11 model weights
├── data/                      # Input images/videos for detection
├── output/                    # Output with detected objects
└── README.md                  # Project documentation
````

---

## ⚙️ Setup Instructions

### Option 1: Run Locally (Anaconda)

1. Clone this repository:

```bash
git clone https://github.com/VHrishita/Python-Object-Detector.git
cd Python-Object-Detector
```

2. Create a virtual environment (optional but recommended):

```bash
conda create -n yolov11-env python=3.10
conda activate yolov11-env
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Download YOLOv11 weights and place them in the `weights/` folder.

5. Run the script:

```bash
python yolov11_detect.py
```
## Train YOLO Models
Option 1. With Google Colab

Click below to acces a Colab notebook for training YOLO models. It makes training a custom YOLO model as easy as uploading an image dataset and running a few blocks of code.

Open In Colab

Option 2. On a Local PC

How to Train YOLO 11 Object Detection Models Locally with NVIDIA

Deploy YOLO Models
The yolo_detect.py script provides a basic example that shows how to load a model, run inference on an image source, parse the inference results, and display boxes around each detected class in the image. This script shows how to work with YOLO models in Python, and it can be used as a starting point for more advanced applications.

To download yolo_detect.py from this repository, issue:

curl --output yolo_detect.py https://raw.githubusercontent.com/EdjeElectronics/Train-and-Deploy-YOLO-Models/refs/heads/main/yolo_detect.py
To run inference with a yolov8s model on a USB camera at 1280x720 resolution, issue:

python yolo_detect.py --model yolov8s.pt --source usb0 --resolution 1280x720
Here are all the arguments for yolo_detect.py:

 The options are:
Image file (example: test.jpg)
Folder of images (example: my_images/test)
Video file (example: testvid.mp4)
Index of a connected USB camera (example: usb0)
--resolution (optional): Resolution in WxH to display inference results at. If not specified, the program will match the source resolution. (example: 1280x720)

---

## 🧠 Features

* Real-time object detection using YOLOv11
* Works with both **images** and **videos**
* Simple, modular Python script
* Google Colab version for easy testing

---

## 📦 Dependencies

* Python 3.8+
* PyTorch
* OpenCV
* NumPy


## 🚀 Future Improvements

* Web interface with Streamlit or Flask
* Integration with webcam feed
* Export results with labels

---

## 🙋‍♂️ Author

**Vempali Hrishita**
\[(mailto:vempalihrishita05@gmail.com)]
GitHub:(https://github.com/VHrishita)

