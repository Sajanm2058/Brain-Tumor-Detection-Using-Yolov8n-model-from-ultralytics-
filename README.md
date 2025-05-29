# Brain-Tumor-Detection-Using-Yolov8n-model-from-ultralytics-
# Brain Tumor Detection Using YOLO

This project implements a **brain tumor detection system** using a YOLO-based object detection model to classify brain MRI images into four categories:  
- **Pituitary**  
- **Meningioma**  
- **Glioma**  
- **No Tumor**

## 📊 Model Performance

| Class          | Images | Instances | Precision | Recall | mAP@0.50 | mAP@0.50:0.95 |
|----------------|--------|-----------|-----------|--------|----------|---------------|
| **All**        | 512    | 554       | 0.953     | 0.934  | 0.968    | 0.797         |
| **Pituitary**   | 135    | 153       | 0.937     | 0.873  | 0.938    | 0.762         |
| **No Tumor**    | 140    | 142       | 0.979     | 0.988  | 0.992    | 0.833         |
| **Meningioma**  | 98     | 98        | 0.977     | 1.000  | 0.983    | 0.836         |
| **Glioma**      | 154    | 161       | 0.920     | 0.876  | 0.959    | 0.755         |

### 🔥 Highlights
- **Overall mAP@0.50**: 96.8%  
- **Overall mAP@0.50:0.95**: 79.7%  
- **Fast Inference**: ~2.2ms per image  
- **Perfect Recall for Meningioma Class**: 100%

---

## 🚀 How to Run the Notebook

1️⃣ **Clone the Repository**:
```bash
git clone <[your-repository-url](https://github.com/Sajanm2058?tab=repositories)>
cd Brain_Tumor_Detection

## 🧠 Dataset
The dataset includes MRI images labeled for Pituitary, Meningioma, Glioma, and No Tumor classes.

