<!-- GitHub-Compatible README HTML -->

<h1 align="center">🎯 Real-Time Object Detection using YOLOv8 + OpenCV + CvZone</h1>

<p align="center">
  <img src="https://img.shields.io/badge/OpenCV-Installed-green?logo=opencv" />
  <img src="https://img.shields.io/badge/YOLOv8-Ultralytics-blueviolet?logo=python" />
  <img src="https://img.shields.io/badge/CvZone-Used-important?logo=python" />
  <img src="https://img.shields.io/badge/Live-Webcam Detection-red" />
</p>

<p align="center">
  <strong>⚡ This project uses Ultralytics YOLOv8 + OpenCV to detect real-world objects through your webcam in real time.</strong>
</p>

<hr>

<h2>✅ Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>YOLOv8 Model (Ultralytics)</li>
  <li>OpenCV</li>
  <li>CvZone</li>
  <li>Webcam or video input</li>
</ul>

<hr>

<h2>📦 Installation</h2>
<p>Use the following pip commands to install the required libraries:</p>

<p>
  🔹 <strong>Install OpenCV:</strong><br>
  <a href="https://pypi.org/project/opencv-python/" target="_blank">
    <img src="https://img.shields.io/badge/pip%20install-opencv--python-orange?logo=pypi" />
  </a>
  <pre><code>pip install opencv-python</code></pre>
</p>

<p>
  🔹 <strong>Install CvZone:</strong><br>
  <a href="https://pypi.org/project/cvzone/" target="_blank">
    <img src="https://img.shields.io/badge/pip%20install-cvzone-blue?logo=pypi" />
  </a>
  <pre><code>pip install cvzone</code></pre>
</p>

<p>
  🔹 <strong>Install Ultralytics YOLOv8:</strong><br>
  <a href="https://pypi.org/project/ultralytics/" target="_blank">
    <img src="https://img.shields.io/badge/pip%20install-ultralytics-blueviolet?logo=pypi" />
  </a>
  <pre><code>pip install ultralytics</code></pre>
</p>

<hr>

<h2>🧠 YOLOv8 Model</h2>
<ul>
  <li>Model used: <code>yolov8n.pt</code> (nano version for faster inference)</li>
  <li>Place the model in the path: <code>../Yolo-Weights/yolov8n.pt</code></li>
  <li>You can download models from: <a href="https://github.com/ultralytics/ultralytics#models" target="_blank">Ultralytics YOLOv8 Models</a></li>
</ul>

<hr>

<h2>🚀 How to Run</h2>

<pre><code># 1. Clone this repository
git clone https://github.com/your-username/yolo-opencv-realtime.git
cd yolo-opencv-realtime

# 2. Run the detection script
python detect.py
</code></pre>

<p>
It will automatically open your webcam and start detecting objects in real-time.
</p>

<hr>

<h2>🛠 Technologies Used</h2>
<ul>
  <li><strong>Python</strong> - Core programming language</li>
  <li><strong>OpenCV</strong> - For image processing and webcam integration</li>
  <li><strong>YOLOv8</strong> - State-of-the-art object detection model</li>
  <li><strong>CvZone</strong> - For drawing styled bounding boxes and text</li>
</ul>

<hr>

<p align="center">
  ⭐ <strong>If you like this project, please consider giving it a star!</strong> ⭐
</p>
