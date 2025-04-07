# Automatic Number Plate Recognition (ANPR) System

![License Plate Detection Demo](demo.gif) *(Add a short GIF/video showing your system in action)*

An end-to-end Automatic Number Plate Recognition system using **YOLOv10** for detection and **PaddleOCR** for text extraction. Designed for real-time processing with region-of-interest (ROI) filtering.

## 🔍 Features
- **YOLOv10 Model**: Custom-trained for high-precision license plate detection
- **PaddleOCR Integration**: Accurate text extraction from detected plates
- **ROI Filtering**: Processes only relevant areas to improve performance
- **Google Colab Ready**: Full notebook support for cloud execution
- **Video Processing**: Handles both images and video streams

## 🛠️ Technical Stack
| Component          | Technology Used          |
|---------------------|--------------------------|
| Object Detection    | Ultralytics YOLOv10      |
| OCR Engine          | PaddleOCR                |
| Language            | Python 3.11              |
| Computer Vision     | OpenCV, CVZone           |
| Environment         | Google Colab (GPU/TPU)   |

## 📂 Project Structure

anpr_Yolo10_PaddleOCR/
├── weights/
│ └── best.pt # Custom-trained YOLOv10 weights
├── data/ # Dataset (images + annotations)
│ ├── train/
│ ├── val/
│ └── data.yaml # YOLO dataset config
├── nr.mp4 # Sample video
├── coco.txt # Class labels ("license_plate")
├── ANPR_Detection.ipynb # Main Colab notebook
└── requirements.txt # Python dependencies


## 📸 Results

Number-Plate-Reader/result1.png
