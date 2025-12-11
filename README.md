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

<h1 align="center">🧠 <b>Brain Tumor Detection using Transfer Learning</b></h1>

<p align="center">
  <b>Deep Learning | VGG-16 | Medical Image Classification</b>
</p>

<hr>

<h2>📌 <b>Summary</b></h2>

<p style="font-size:16px; line-height:1.6;">
This project focuses on building an intelligent prediction model for <b>classifying tumor vs. non-tumor brain X-ray images</b> using <b>Transfer Learning (VGG-16)</b>.
<br><br>
The dataset was obtained from <b>Kaggle</b>, and extensive <b>preprocessing & image augmentation</b> techniques were applied to improve model robustness and performance.
<br><br>
The final dataset was split in an <b>80:20 train-test ratio</b>. A pretrained <b>VGG-16 network</b> was fine-tuned for tumor classification. After training, the model was evaluated using <b>accuracy, loss curves, and other key performance metrics</b>.
</p>

<hr>

2.Drowsiness Detection System
📌 Summary
This project focuses on identifying whether a car driver is alert or drowsy in real time. The system is implemented using a Raspberry Pi, with live video captured through a Pi Camera. Using MediaPipe, the model extracts 468 facial landmark points, enabling accurate 3D feature extraction.
For this project, key facial features around the eyes and mouth are used. Based on these features, the Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR) are calculated to detect signs of drowsiness such as tired eyes and frequent yawning. Threshold values are set for EAR and MAR; when the real-time values cross these thresholds, the system classifies the driver as drowsy.
