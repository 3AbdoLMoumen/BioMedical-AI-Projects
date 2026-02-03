# 📊 BioMedical AI Projects

This repository contains code for **BioMedical AI** projects I have developed and shared on LinkedIn, focusing on medical image analysis and disease classification using deep learning techniques.

### 🚀 Key Models & Techniques
- **Semantic Segmentation** – Implemented using **U-Net** and its advanced variants: **U-Net++** and **Attention U-Net++**  
- **Classification** – Built using **custom CNN architectures** and **transfer learning** with fine-tuned pre-trained models
- **Grad Cams** - for XAI
- **Data Augmentation and Preprocessing**

### 💡 Notes
- Some projects are early-stage and may include outdated practices, e.g., loading entire datasets into RAM instead of using efficient data loaders, agressive augmentation in low data regimes 
- These notebooks are intended for learning, experimentation, and reproducibility in biomedical AI.  

### 🗂 Projects Included
| Project | Description | Model/Approach |
|---------|-------------|----------------|
| `brain-tumor-segmentation-Unet.ipynb` | Segmenting brain tumors from MRI scans | U-Net |
| `cardio-seg-attention-unet++.ipynb` | Cardiac structure segmentation from medical imaging | Attention U-Net++ |
| `retinal-disease-classification.ipynb` | Detecting retinal diseases from fundus images | Transfer Learning MobileNet 2|
| `retina-vessel-segmentation-unet++.ipynb` | Retinal blood vessel segmentation | U-Net++ |
| `breast-cancer-classification.ipynb` | Classifying breast cancer images (benign/malignant) | CNN |
| `kidney-stone-detection.ipynb` | Detecting kidney stones from medical scans | YOLO |
| `retinal-oct-classification.ipynb` | OCT retinal image classification | CNN |
