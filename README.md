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
  <b>Deep Learning | VGG-19 | Medical Image Classification</b>
</p>



<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
This project focuses on building an intelligent prediction model for <b>classifying tumor vs. non-tumor brain X-ray images</b> using <b>Transfer Learning (VGG-16)</b>.
<br><br>
The dataset was obtained from multipe sources, and extensive <b>preprocessing & image augmentation</b> techniques were applied to improve model robustness and performance.
<br><br>
The final dataset was split in an <b>80:20 train-test ratio</b>. A pretrained <b>VGG-19 network</b> was fine-tuned for tumor classification. After training, the model was evaluated using <b>accuracy, loss curves, and other key performance metrics</b>.
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
This project aims to monitor the safety of construction site workers using <b>YOLOv8 (You Only Look Once)</b> with custom training of dataset.
</p>

<p style="font-size:16px; line-height:1.6;">
Key features of the system include:
</p>

<ul style="font-size:16px; line-height:1.6;">
  <li><b>Safety Equipment Detection:</b> The model checks whether workers are wearing essential safety gear, such as goggles, safety jackets, helmets, and gloves.</li>
  <li><b>Danger Zone Monitoring:</b> Danger zones in the construction site are manually defined using bounding boxes. If a worker’s bounding box overlaps with a danger zone, the system triggers an alert to prevent accidents.</li>
</ul>

<hr>

<h2 align="left">📊 <b>AI Dashboard for Project Governance</b></h2>

<p align="left">
  <b>Dash | Plotly | RAG Indicators | Real-Time Analytics | Project Management</b>
</p>

<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
Developed a real-time interactive <b>AI dashboard using Dash and Plotly</b> to monitor project progress, generate reports, and provide team-wise performance insights. The dashboard consolidates multiple data sources and visualizations for comprehensive project governance.
</p>

<p style="font-size:16px; line-height:1.6;">
<b>Key Features / Process:</b>
</p>

<ul style="font-size:16px; line-height:1.6;">
  <li>Interactive visualizations for project progress and team-wise performance.</li>
  <li>Integration of <b>RAG (Red-Amber-Green) indicators</b> to quickly highlight risks and track project status.</li>
  <li>Real-time analytics enabling continuous monitoring and proactive decision-making.</li>
</ul>

<p style="font-size:16px; line-height:1.6;">
<b>Outcome:</b> The dashboard enabled <b>data-driven project management</b>, allowing stakeholders to identify risks early, make informed decisions, and improve overall project efficiency.
</p>

<hr>


<h2 align="left">📧 <b>Phishing Email Detection using TabNet</b></h2>

<p align="left">
  <b>TabNet | NLP Feature Engineering | Tabular Deep Learning</b>
</p>

<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
This project focuses on detecting phishing (spam) emails using <b>TabNet</b>, a deep learning model designed specifically for tabular data. The dataset contains, containing two main columns: the email message and its label (ham/spam).
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

<h2 align="left">🖼️ <b>Restoration of Image Watermark using Diffusion Model with U-Net</b></h2>

<p align="left">
  <b>Diffusion Model | U-Net Backbone | Image-to-Image Translation | EasyOCR | Computer Vision</b>
</p>

<h3>📌 <b>Summary</b></h3>

<p style="font-size:16px; line-height:1.6;">
This project focuses on restoring watermarks from images using a <b>diffusion model with a U-Net backbone</b>. The dataset is sourced from and contains diverse images including nature, animals, and scenery and so on. Each image has different watermark text at random positions. Additional <b>white noise</b> and <b>blur</b> are added to simulate real-world image degradation.
</p>

<p style="font-size:16px; line-height:1.6;">
For training:
</p>

<ul style="font-size:16px; line-height:1.6;">
  <li><b>Input:</b> noisy images containing watermarks</li>
  <li><b>Output:</b> clean watermark-only images</li>
</ul>

<p style="font-size:16px; line-height:1.6;">
The dataset is split in an <b>80:20 ratio</b> for training and testing. A <b>denoising diffusion model</b> is trained with a <b>U-Net architecture</b> to iteratively reconstruct watermark regions from noisy inputs. At each diffusion step, the U-Net predicts the noise to be removed, gradually restoring the clean watermark image.
</p>

<p style="font-size:16px; line-height:1.6;">
During evaluation, the restored watermark images are processed using <b>EasyOCR</b> to extract the text. Model performance is measured based on the accuracy of the recovered watermark text.
</p>

<p style="font-size:16px; line-height:1.6;">
This approach leverages the <b>generative capabilities of diffusion models</b> combined with the <b>localization strength of U-Net</b>, enabling robust restoration of subtle watermark patterns even under heavy noise and blur.
</p>

<hr>
