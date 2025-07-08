# Crowd Monitoring Using Computer Vision

A real-time zone-specific crowd monitoring system that uses **YOLOv8**, **Detectron2**, and **Supervision** to detect and count people within polygon-defined regions of video frames. The project is designed for crowd analysis, surveillance, and smart city applications, enabling automated annotation and scalable processing of video data.

---

## 📌 Features

- ✅ Real-time object detection using **YOLOv8** and **Detectron2**
- ✅ Zone-specific people counting using polygonal ROI (Region of Interest)
- ✅ Frame preprocessing and annotation using **OpenCV** and **NumPy**
- ✅ Integrated with **Supervision**'s `PolygonZone` for defining and tracking specific areas
- ✅ Fully automated pipeline for inference, counting, and annotation
- ✅ Optimized for large video datasets

---

## 📽️ Demo

> Coming soon: GIF/Video showing live people detection in polygon zones with counts.

---

## 🧠 Tech Stack

| Component    | Description                            |
| ------------ | -------------------------------------- |
| YOLOv8       | Real-time object detection (Ultralytics)|
| Detectron2   | Facebook AI's object detection toolkit |
| Supervision  | High-level video processing and zoning |
| OpenCV       | Video processing and annotation        |
| NumPy        | Numerical operations                   |
| Python       | Backend logic and automation           |

---

## 📁 Project Structure

crowd-monitoring/
├── results/                            # Output files: annotated videos/images
├── dmart_mall.ipynb                    # Notebook for initial mall video testing
├── final_monitoring_people_project_.ipynb  # Final integrated people monitoring notebook
├── req.txt                             # Python package dependencies
├── .gitattributes                      # Git settings (e.g., for Jupyter diff)
└── README.md                           # Project overview (this file)

