# Helmet Violation Detection using YOLOv10, YOLOv11, and YOLOv12  
<img width="1160" height="901" alt="image" src="https://github.com/user-attachments/assets/5e66ac3b-3bc6-4f40-823b-696b299f3872" />

## 🌐 Live Demo & Slides  
- 🔗 [Try the Web App](https://gothelmet.vercel.app/) – Upload an image and see detection results in real-time.  
- 🎞️ [View Presentation Slides](https://www.canva.com/design/DAGwkFGjdl8/hmHpOYOtcLz0ney9ajUBWg/edit?utm_content=DAGwkFGjdl8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) – Overview of the project, methodology, and results.  

---

## 📌 Overview  
This repository contains the implementation of my undergraduate thesis project: **Helmet Violation Detection for Motorcyclists** using the **YOLO (You Only Look Once)** family of object detection models, specifically **YOLOv10, YOLOv11, and YOLOv12**.  

The goal of this project is to automatically detect and classify whether motorcycle riders are wearing helmets or not, based on CCTV footage. This research compares the performance of different YOLO versions in terms of **accuracy, precision, recall, F1-score, mAP@0.5, and inference time**.  

---

## 🎯 Objectives  
- Develop an AI-based system to detect helmet violations from real-world CCTV images.  
- Compare the performance of YOLOv10, YOLOv11, and YOLOv12 in this task.  
- Provide insights into which YOLO model is most suitable for traffic law enforcement.  

---

## 🗂️ Dataset  
- Source: CCTV images of motorcyclists (collected and preprocessed for research purposes).  
- Classes:  
  - `withHelmet`  
  - `withoutHelmet`  
- Preprocessing steps included: resizing, annotation (bounding boxes), and augmentation.  

---

## ⚙️ Methodology  
1. **Data Collection & Annotation**  
   - Images annotated using [Roboflow/LabelImg/etc.].  
   - Stored in YOLO format (txt files with class and bounding box coordinates).  

2. **Model Training**  
   - Framework: [Ultralytics YOLO / PyTorch].  
   - Models: YOLOv10, YOLOv11, YOLOv12.  
   - Training performed with different configurations (epochs, batch size, image size).  

3. **Evaluation Metrics**  
   - Precision  
   - Recall  
   - F1-score  
   - mAP@0.5  
   - Inference Time (ms/image)  

---

## 📊 Results  

| Model   | Precision | Recall | F1-score | mAP@0.5 | Inference Time |
|---------|-----------|--------|----------|---------|----------------|
| YOLOv10 | 0.910     | 0.896  | 0.903    | 0.942   | **23.3 ms**    |
| YOLOv11 | 0.920     | **0.898** | **0.909** | **0.952** | 30 ms         |
| YOLOv12 | **0.922** | 0.892  | 0.907    | 0.943   | 41.4 ms        |

---

## 📚 References

* Ultralytics YOLO: [https://github.com/ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)
* Relevant research papers on YOLOv10, YOLOv11, and YOLOv12

---

## ✍️ Author

**Miftahur Rizki**
Data Science Undergraduate | Telkom University
📧 [your email] | 🔗 [LinkedIn/GitHub profile]

---

Mau gw bikinin versi **academic style** yang serius (kaya skripsi) atau **casual style** (lebih gampang dibaca orang di GitHub, kaya proyek open source)?
