# 😷 Real‑Time Face Mask Detection

A Python‑based application that uses OpenCV, a pre‑trained SSD face detector, and a custom CNN mask classifier to detect whether people in your webcam feed are wearing masks. Perfect for demos, learning, or prototyping safety monitoring tools.

---

## 🚀 Features

- **Real‑time inference** on webcam stream  
- **SSD‑based face detection** using Caffe (`deploy.prototxt` + `.caffemodel`)  
- **Mask vs. No‑Mask classification** with a fine‑tuned MobileNetV2 CNN  
- **Clean bounding boxes** & probability labels  

---

## 📂 Project Structure
face-mask-detection/  
├── deploy.prototxt  
├──res10_300x300_ssd_iter_140000.caffemodel  
├──mask_detector.model  
├──detect_mask_video.py  
├── README.md  
