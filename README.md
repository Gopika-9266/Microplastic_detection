
# 🌊 Microplastic Detection using Detectron2 
An AI-powered deep learning system that automatically detects and segments microplastics in microscopic water sample images using Detectron2, enabling faster and more accurate marine pollution monitoring.**

---

# 📌 Overview

Microplastics are tiny plastic particles (less than 5 mm in size) that have become one of the most serious threats to marine ecosystems. Traditional methods of detecting microplastics involve manual microscopic examination, which is time-consuming, labor-intensive, and prone to human error.

The **Microplastic Detection using Detectron2** project leverages **Instance Segmentation** and **Object Detection** techniques to automatically identify microplastic particles from microscopic images of ocean water samples. Built using **Detectron2** and **Mask R-CNN**, the system provides accurate detection results, helping researchers and environmental agencies monitor marine pollution more efficiently.

---

# 🎯 Objectives

- Detect microplastics automatically from microscopic images.
- Reduce manual inspection time.
- Improve detection accuracy using Deep Learning.
- Assist researchers in marine pollution analysis.
- Provide an efficient and scalable monitoring solution.

---

# ✨ Features

- 🔬 Automatic Microplastic Detection
- 🤖 Detectron2-based Deep Learning Model
- 🎯 Instance Segmentation using Mask R-CNN
- 📷 High-Resolution Image Processing
- 📊 Performance Evaluation Metrics
- ⚡ Fast Inference
- 🌊 Supports Ocean Water Sample Analysis
- 📈 Accurate Detection Visualization

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Detectron2 | Object Detection Framework |
| PyTorch | Deep Learning Framework |
| OpenCV | Image Processing |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Roboflow | Dataset Annotation |
| COCO Dataset Format | Dataset Organization |
| CUDA | GPU Acceleration |

---

# 🔄 System Workflow

```text
Water Sample Collection
          │
          ▼
Microscopic Image Acquisition
          │
          ▼
Image Annotation (Roboflow)
          │
          ▼
Dataset Preparation (COCO Format)
          │
          ▼
Image Preprocessing & Augmentation
          │
          ▼
Model Configuration (Detectron2)
          │
          ▼
Model Training (Mask R-CNN)
          │
          ▼
Microplastic Detection
          │
          ▼
Performance Evaluation
          │
          ▼
Prediction Visualization
```

---

# 📸 Project Screenshots

## 📷 Input Microscopic Image

![Input](https://github.com/user-attachments/assets/fd321014-be1f-4091-86b7-6e5369c7c8cb)


---

## 🔬 Detected Microplastics

![Detected Microplastics](https://github.com/user-attachments/assets/7e8fca85-3511-4224-9b32-28350cae919d)

---

## 📊 Final Prediction

![Final Prediction](https://github.com/user-attachments/assets/a10f864e-be67-45de-8daa-af54b9dbd379)

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/Microplastic-Detection-Detectron2.git

cd Microplastic-Detection-Detectron2
```

---

## Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## Install Detectron2

```bash
pip install detectron2
```

---

## Run the Detection Script

```bash
python detect.py
```

---

## Train the Model

```bash
python train.py
```

---

# 🚀 How It Works

### Step 1

Collect ocean water samples from coastal regions.

---

### Step 2

Capture microscopic images of filtered water samples.

---

### Step 3

Annotate microplastic particles using Roboflow.

---

### Step 4

Convert the annotated dataset into COCO format.

---

### Step 5

Configure the Detectron2 model using a pre-trained Mask R-CNN architecture.

---

### Step 6

Train the model using the annotated dataset.

---

### Step 7

Provide a microscopic image as input.

---

### Step 8

The trained model detects and segments the microplastic particles.

---

### Step 9

The final prediction image with segmentation masks and bounding boxes is displayed.

---

# 📊 Performance Metrics

| Metric | Value |
|---------|--------|
| Accuracy | **90%** |
| Precision | **93%** |
| Recall | **92%** |
| Inference Time | **~40 ms/Image (GPU)** |

---

# 📈 Results

The proposed model successfully detects microplastic particles from microscopic images with high accuracy.

### Key Outcomes

- ✅ Automated Microplastic Detection
- ✅ Accurate Instance Segmentation
- ✅ Faster Analysis Compared to Manual Methods
- ✅ Reliable Detection Performance
- ✅ Supports Marine Pollution Monitoring

---

# 🌍 Applications

- Marine Pollution Monitoring
- Environmental Research
- Ocean Conservation Studies
- Water Quality Assessment
- Coastal Ecosystem Analysis
- Academic Research
- Smart Environmental Monitoring Systems

---

# 💡 Advantages

- Reduces manual inspection effort.
- High detection accuracy.
- Fast inference speed.
- Supports large-scale environmental monitoring.
- Scalable for future deployments.
- Improves consistency in microplastic analysis.

---

# 🔮 Future Enhancements

- 🚁 Drone-based real-time marine monitoring.
- 🌊 Underwater robotic deployment.
- ☁️ Cloud-based detection platform.
- 📱 Mobile application support.
- 🧬 Classification of different microplastic types.
- 📊 Automatic density estimation and pollution mapping.
- 🤖 Integration with IoT-enabled environmental monitoring systems.

---

# 🌱 Environmental Impact

This project contributes to sustainable marine ecosystem monitoring by providing an automated solution for identifying microplastic pollution.

The developed system supports environmental researchers and conservation agencies in making faster and more informed decisions, contributing towards **United Nations Sustainable Development Goal (SDG) 14 – Life Below Water**.
