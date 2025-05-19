# Python-Object-Detector
A real-time object detection project using **YOLOv11** and Python. This tool allows you to detect objects in images or videos using a pretrained YOLOv11 model.


## 📁 Project Structure

```bash
yolo-object-detector/
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

