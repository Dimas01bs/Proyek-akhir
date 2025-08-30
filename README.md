
# Object Detection with YOLOv8 🚀

## 📌 Project Description
This project implements **object detection** using **YOLOv8** (Ultralytics) in a Google Colab GPU environment.  
The model is trained and tested on a dataset provided by **Roboflow**, and evaluated on sample images to detect multiple objects such as people, animals, and vehicles.  

The main objective of this project is to demonstrate the workflow of **training**, **inference**, and **visualization** using YOLOv8, providing an introduction to real-time computer vision tasks like object detection.  

---

## ⚙️ Technologies Used
- **Python 3 (Google Colab Environment)** → main programming language.  
- **Ultralytics YOLOv8** → framework for object detection tasks.  
  - Pre-trained model: `yolo11n.pt`  
  - Task mode: `detect`  
- **PyTorch with CUDA Support** → backend deep learning framework (GPU Tesla T4).  
- **Roboflow Dataset** → dataset source for training and evaluation.  
- **IPython & Google Colab Utilities** → for visualization and GPU acceleration.  
- **Supporting Libraries**:  
  - `os` → directory and file management.  
  - `matplotlib` / image display → visualization of detection outputs.  

---

## 🚀 How to Run
1. Open the notebook in **Google Colab**.  
2. Change runtime to **GPU** for faster processing.  
3. Install dependencies:  
   ```bash
   pip install ultralytics
