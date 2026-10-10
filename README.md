# Vision-Based Inspection & Classification of Screws and Bits

An end-to-end deep learning benchmark comparing **YOLOv8** and **YOLO-NAS** for real-time object detection of screws and identification of bits based on WERA-64 bits kit .

---

## 📌 Project Overview

Automated quality control and component classification in manufacturing assembly lines require both high precision and real-time processing capabilities. This repository contains the code, evaluation pipelines, and documentation from my Master's thesis.

The project evaluates state-of-the-art vision architectures (**YOLOv8** by Ultralytics vs. **YOLO-NAS** by Deci AI/SuperGradients) across key metrics:
- **Detection Accuracy:** Precision, Recall, and mAP@0.5 / mAP@0.5:0.95.
- **Inference Latency:** Frame-rate (FPS) performance under constrained edge hardware setups.
- **Robustness:** Performance under varying lighting conditions, component orientations, and occlusion.


---
🛠️ Tech Stack & Frameworks

    Deep Learning Frameworks: PyTorch, Ultralytics (YOLOv8), SuperGradients (YOLO-NAS)
    Computer Vision: OpenCV, PIL, Albumentations
    Data & Metrics: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn
    Environment: Jupyter Notebook, Python 3.10+
---

## 📂 Repository Structure

```text
masters-thesis-screws-and-bits/
├── README.md                               # Showcase & project documentation
├── requirements.txt                        # Core dependencies
├── .gitignore                         # Git rules for ignoring weights & zips
├── docs/
│   ├── MastersThesis_ScrewsAndBits.pdf     # Complete Master's thesis report
│   └── MasterColloquium_ScrewsAndBits.pptx # Presentation deck
└── notebooks/
    ├── yolov8_experiments.ipynb   # YOLOv8 model training & evaluation
    └── yolonas_experiments.ipynb  # YOLONAS model training & evaluation
└── Results/
    ├──Picture results             #YOLOv8 and YOLONAS picture results 
    └──Video results               #YOLOv8 and YOLONAS video results

## 🔹 Installation

1. **Clone the repository**
```bash
git clone https://github.com/muhammadazhar1991/AI-based-IIoT-Anomaly-Detection.git
cd masters-thesis-screws-and-bits

## 🔹 Create a virtual environment (optional)

python -m venv venv
source venv/bin/activate      # Linux / Mac
venv\Scripts\activate         # Windows#

## 🔹 Install dependencies

pip install -r requirements.txt

## 🔹 How to Run

open the files in jupyter notebook environment

## 🔹 Requirements

Python 3.10

Libraries listed in requirements.txt

## 🔹 Contact

GitHub: https://github.com/muhammadazhar1991

Email: engr.azher.ma@gmail.com
