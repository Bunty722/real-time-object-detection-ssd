# real-time-object-detection-ssd
A real-time object detection system using MobileNet SSD and OpenCV. Detects common objects from webcam video stream with bounding boxes and confidence scores.
# Real-Time Object Detection with MobileNet SSD

A real-time object detection system using OpenCV’s Deep Neural Network (DNN) module and a pre-trained MobileNet SSD model. It detects everyday objects (like people, cars, dogs, etc.) from a webcam video stream.

## 🔧 Example Python Code

```python
import cv2
net = cv2.dnn.readNetFromCaffe("models/MobileNetSSD_deploy.prototxt.txt", "models/MobileNetSSD_deploy.caffemodel")
```

<pre> ## 📁 Project Structure ``` real-time-object-detection-ssd/ ├── models/ # Pretrained model files │ ├── MobileNetSSD_deploy.prototxt.txt │ └── MobileNetSSD_deploy.caffemodel ├── notebook/ │ └── real_time_detection.ipynb # Jupyter notebook version ├── requirements.txt # List of Python dependencies ├── README.md └── LICENSE ``` </pre>

## 📦 Installation

### 1. Clone the repo:
Start by cloning the repository to your local machine:

```bash
git clone https://github.com/your-username/real-time-object-detection-ssd.git
cd real-time-object-detection-ssd
```
2. Install dependencies:
You can install all required Python packages using pip:
```
pip install -r requirements.txt
```
3. Run the project:
Option 1: Using Jupyter Notebook If you want to run the code in Jupyter Notebook, navigate to the notebook/ folder and start the notebook:
```
cd notebook
jupyter notebook
```
## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

