<h1 align="center">🚀 <b>Data Science & Machine Learning Projects</b></h1>

<div align="center" style="
     background:#f5f5f5;
     padding:12px 20px;
     margin-top:10px;
     border-radius:10px;
     width:80%;
">
  <p style="font-size:15px;">
    This repository contains the summary of my academic projects.
  </p>
</div>

<hr>

<h2 align="left">🧠 <b>Brain Tumor Detection using Transfer Learning</b></h2>

<p align="left">
  <b>Deep Learning | VGG-16 | Medical Image Classification</b>
</p>

<hr>

<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
This project focuses on building an intelligent prediction model for <b>classifying tumor vs. non-tumor brain X-ray images</b> using <b>Transfer Learning (VGG-16)</b>.
<br><br>
The dataset was obtained from <b>Kaggle</b>, and extensive <b>preprocessing & image augmentation</b> techniques were applied to improve model robustness and performance.
<br><br>
The final dataset was split in an <b>80:20 train-test ratio</b>. A pretrained <b>VGG-16 network</b> was fine-tuned for tumor classification. After training, the model was evaluated using <b>accuracy, loss curves, and other key performance metrics</b>.
</p>

<hr>

<h2 align="left">😴 <b>Drowsiness Detection System</b></h2>
<p align="left">
  <b>MediaPipe | Raspberry Pi | Real-Time Computer Vision</b>
</p>
<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
This project focuses on detecting whether a car driver is <b>alert or drowsy in real time</b>. The system is implemented using a <b>Raspberry Pi</b>, with continuous video input captured through a <b>Pi Camera</b>.
<br><br>
Using <b>MediaPipe</b>, the system extracts <b>468 facial landmark points</b>, enabling highly accurate <b>3D facial feature tracking</b>. For this project, the primary focus is on critical facial regions such as the <b>eyes</b> and <b>mouth</b>.
<br><br>
Key features such as the <b>Eye Aspect Ratio (EAR)</b> and <b>Mouth Aspect Ratio (MAR)</b> are computed from the extracted landmarks to detect signs of drowsiness, including <b>tired/blinking eyes</b> and <b>frequent yawning</b>.
<br><br>
Threshold values are set for both EAR and MAR. When real-time values cross these thresholds, the system actively flags the driver as <b>drowsy</b>.
</p>

<hr>
<hr>
<h1 align="left">🏗️ <b>Construction Safety Management using YOLO</b></h1>

<p align="left">
  <b>YOLOv3 | ImageNet | Real-Time Safety Monitoring</b>
</p>



<h2>📌 <b>Summary</b></h2>

<p style="font-size:16px; line-height:1.6;">
This project aims to monitor the safety of construction site workers using <b>YOLOv3 (You Only Look Once)</b> with pretrained weights from <b>ImageNet</b>.
</p>

<p style="font-size:16px; line-height:1.6;">
Key features of the system include:
</p>

<ul style="font-size:16px; line-height:1.6;">
  <li><b>Safety Equipment Detection:</b> The model checks whether workers are wearing essential safety gear, such as goggles, safety jackets, helmets, and gloves.</li>
  <li><b>Danger Zone Monitoring:</b> Danger zones in the construction site are manually defined using bounding boxes. If a worker’s bounding box overlaps with a danger zone, the system triggers an alert to prevent accidents.</li>
</ul>

<hr>
