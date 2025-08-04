# ♻️ Waste Classification App using YOLOv8 and Streamlit

This project is a real-time waste classification web app built using **YOLOv8** (Ultralytics) and **Streamlit**. It allows users to upload an image or use their webcam to detect waste categories such as plastic, metal, glass, etc.

## 🚀 Features

- 📸 Upload image and perform object detection.
- 🎥 Detect waste from webcam or YouTube video.
- 📦 Built using YOLOv8 for accurate real-time predictions.
- 🖼️ Default sample image preview for user testing.
- 🔍 Adjustable confidence slider for detection threshold.

## 🧠 Model Info

- The app loads a trained YOLOv8 model:  
  `weights/yolov8_waste.pt`
- You can replace this with your own `.pt` model file for custom datasets.

## 🛠 Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| UI          | Streamlit          |
| Detection   | YOLOv8 (Ultralytics) |
| Image/Video | OpenCV, Pafy       |
| Code        | Python (modular design) |

## Requirements

pip install -r requirements.txt

## Run the app

streamlit run app.py

