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
<h2 align="left">🏗️ <b>Construction Safety Management using YOLO</b></h2>

<p align="left">
  <b>YOLOv3 | ImageNet | Real-Time Safety Monitoring</b>
</p>



<h3>📌 <b>Summary</b></h3>

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


<h2 align="left">📧 <b>Phishing Email Detection using TabNet</b></h2>

<p align="left">
  <b>TabNet | NLP Feature Engineering | Tabular Deep Learning</b>
</p>

<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
This project focuses on detecting phishing (spam) emails using <b>TabNet</b>, a deep learning model designed specifically for tabular data. The dataset is taken from <b>Kaggle</b>, containing two main columns: the email message and its label (ham/spam).
</p>

<p style="font-size:16px; line-height:1.6;">
Extensive NLP feature engineering is performed to convert raw text into numerical features:
</p>

<ul style="font-size:16px; line-height:1.6;">
  <li>Stopword count, URL count, email-ID count, and misspelled words count</li>
  <li><b>POS (Part-of-Speech) tagging:</b> counts of nouns, verbs, adjectives, pronouns, etc.</li>
  <li><b>NER (Named Entity Recognition):</b> counts of names, locations, dates, organizations</li>
  <li><b>LDA (Latent Dirichlet Allocation):</b> topic modeling to identify themes such as fake promotions, offers, lottery scams, which commonly indicate spam</li>
</ul>

<p style="font-size:16px; line-height:1.6;">
After creating the tabular dataset, the dataset is split into an <b>80:20 ratio</b> for training and testing. The final model is built using <b>TabNet</b>, which works well on sparse data.
</p>

<hr>
