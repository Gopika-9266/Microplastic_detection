# 🌊 Microplastic Detection using Detectron2 for Oceanic Monitoring

## 🎯 Objective

To design and implement a deep learning-based pipeline using **Detectron2** for **automated detection of microplastics** in oceanic water samples collected along the **southern coastline of India**. The goal is to assist environmental monitoring agencies and marine researchers by providing a scalable, AI-powered solution for real-time and accurate microplastic detection.

---

## 🔍 Project Motivation

Microplastics—tiny plastic particles less than 5mm in size—have infiltrated global marine ecosystems, threatening biodiversity and entering human food chains. Traditional detection methods are **manual, time-consuming**, and **labor-intensive**. By harnessing the capabilities of **instance segmentation and object detection models**, we propose a smarter, **automated alternative** using **Detectron2**.

---

## 📊 Algorithmic Pipeline

> A step-by-step breakdown of our AI-driven detection system:

### Step 1: Data Acquisition
- Collect water samples from coastal regions of Tamil Nadu and Kerala.
- Use microscopy to capture high-resolution images of filtered microplastic residues.

### Step 2: Data Annotation
- Annotate microplastic particles in each image using Roboflow's labeling interface.
- Export datasets in COCO format, divided into **train**, **validation**, and **test** sets.

### Step 3: Environment & Library Setup
- Install **Detectron2**, PyTorch, CUDA, and other dependencies.
- Configure system paths and environment for GPU acceleration.

### Step 4: Model Configuration
- Load pre-trained **Mask R-CNN** or **Faster R-CNN** model from Detectron2’s model zoo.
- Fine-tune hyperparameters like learning rate, batch size, number of iterations.

### Step 5: Data Augmentation
- Apply transformations: horizontal/vertical flips, Gaussian noise, contrast adjustment.
- Enhances generalization and robustness of the model across diverse oceanic imagery.

### Step 6: Model Training
- Train the model on annotated microplastic datasets.
- Use checkpointing and periodic evaluation for model optimization.

### Step 7: Performance Evaluation
- Evaluate using **mean Average Precision (mAP@50:70)** and other key metrics:
  - **Accuracy**: 90%
  - **Precision**: 93%
  - **Recall**: 92%

### Step 8: Deployment & Visualization
- Export the trained model (`model_final.pth`) for integration.
- Visualize predictions via matplotlib and Detectron2's visualizer.
- Build inference-ready pipeline for real-world deployment.

---

## 💡 Sample Output

### 🖼️ Input Image:
![Input](https://github.com/user-attachments/assets/fd321014-be1f-4091-86b7-6e5369c7c8cb)

### 🔬 Microplastic Detection:
![Detected Microplastics](https://github.com/user-attachments/assets/7e8fca85-3511-4224-9b32-28350cae919d)

### 📌 Final Output:
![Final Prediction](https://github.com/user-attachments/assets/a10f864e-be67-45de-8daa-af54b9dbd379)

---

## 📈 Performance Summary
• Accuracy : 90%

• Precision : 93%

• Recall : 92%

• Inference Time : ~40 ms/image (GPU)


- **High precision** ensures low false-positive detection.
- **Strong recall** highlights model’s ability to capture most microplastic instances.

---

## 🧠 Inferences & Future Scope

The developed microplastic detection framework exhibits **remarkable detection reliability** and is capable of supporting **automated marine pollution analysis**. Its strengths lie in:

- **Scalability** for long-term ecological monitoring.
- **Speed and accuracy** outperforming traditional visual/manual methods.
- **Real-time deployability** on marine drones, underwater ROVs, or edge devices.

### 🔭 Future Enhancements

- Integrate real-time drone imaging and edge computing.
- Expand to **multi-modal datasets** including hyperspectral imagery.
- Extend the model to identify microplastic **types and densities**.

---

## 🌐 Impact Statement

This project is a critical step toward **AI-powered marine sustainability**. By automating microplastic detection, we contribute a **scalable, reproducible, and efficient** methodology for mitigating marine plastic pollution, supporting the **United Nations SDG 14 – Life Below Water**.


