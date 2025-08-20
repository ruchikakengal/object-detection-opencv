# Object Detection using (OpenCV & Python)

This project demonstrates **Object Detection** using the **OpenCV DNN module** with popular deep learning models such as **YOLO, SSD, and Faster R-CNN**.
The OpenCV `dnn` module supports running inference on pre-trained deep learning models from frameworks like **OpenCV & Python , and TensorFlow**.

---

## 🔍 Supported Detection Frameworks

* **YOLO (You Only Look Once)**
* **SSD (Single Shot MultiBox Detector)**
* **Faster R-CNN**

(OpenCV recently added support for running **YOLO/DarkNet** models directly.)

---

## 📦 Dependencies

Install the required Python libraries:

```bash
pip install numpy opencv-python
```

> ⚠️ Note: Compatibility with **Python 2.x** is not officially tested.

---

## 🚀 YOLO (You Only Look Once)

### Step 1: Download Pre-trained Weights

Download the pre-trained **YOLOv3 weights** from the official site:

```bash
wget https://pjreddie.com/media/files/yolov3.weights
```

### Step 2: Run Object Detection

Make sure the following files are present in the working directory:

* `yolov3.cfg`
* `yolov3.weights`
* `yolov3.txt` (class labels file)


### General Command Format

```bash
python yolo_opencv.py --image /path/to/input/image \
                      --config /path/to/config/file \
                      --weights /path/to/weights/file \
                      --classes /path/to/classes/file
```

---

## 📸 Sample Output

<img width="1617" height="889" alt="Screenshot 2025-08-20 204520" src="https://github.com/user-attachments/assets/ed5f7294-704a-4b5f-955c-caf6ba4c4f0f" />


---

## 📚 Additional Tools

For easier object detection, you can use **cvlib**, which allows detecting common objects with just a single function call:

```python
from cvlib.object_detection import detect_common_objects
```

---

## 📝 Upcoming

* [ ] Add **SSD** example
* [ ] Add **Faster R-CNN** example

---

✨ This project is a simple starting point for learning **object detection with OpenCV & Deep Learning**.

---



