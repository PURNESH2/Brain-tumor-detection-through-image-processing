# 🧠 Brain Tumor Detection using Image Processing 
This project focuses on the detection and classification of brain tumors using MRI images through advanced image processing and deep learning models. We compare the performance of Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to identify tumor presence efficiently and accurately.

## 📌 Objective

To build an automated diagnostic tool that can:
- Detect the presence of brain tumors from MRI scans.
- Highlight tumor regions using segmentation techniques.
- Classify images based on the presence or absence of tumors.
- Compare CNNs and ViTs for performance and generalizability.

## 🔬 Technologies Used

- **Python**
- **OpenCV** – for image preprocessing and enhancement.
- **NumPy** – numerical computations.
- **Matplotlib** – data and image visualization.
- **Convolutional Neural Networks (CNNs)** – for local feature extraction.
- **Vision Transformers (ViTs)** – for capturing global context in image data.
- **Jupyter Notebook** – for prototyping and model experimentation.

## 🧪 Features Implemented

- **Image Enhancement**: Histogram equalization and noise reduction.
- **Segmentation Techniques**: Morphological gradient, thresholding, and contouring.
- **Feature Extraction**: Tumor region masking and analysis (area, perimeter).
- **Model Comparison**:
  - CNN: Better generalization on test data.
  - ViT: Higher training accuracy, more sensitive to overfitting.

## 🏥 Medical Use Case

- Provides a consistent, non-invasive second-opinion tool for radiologists.
- Reduces diagnostic time and human error.
- Helpful in resource-limited environments without specialist availability.

## 💡 Results

| Model | Training Accuracy | Test Accuracy |
|-------|-------------------|---------------|
| CNN   | ~95%              | **92%**       |
| ViT   | **98%**           | ~88%          |

CNN models showed better generalization, making them more suitable for deployment in clinical environments.

## 📁 Repository Structure

```
📦 brain-tumor-detection/
├── 📜 README.md
├── 📓 Brain_Tumor_Detection.ipynb
├── 📁 dataset/
│   ├── yes/    # MRI images with tumor
│   └── no/     # MRI images without tumor
├── 📜 requirements.txt
└── 📊 results/  # Saved figures and masks
```

## 📌 Future Improvements

- Real-time tumor detection integration with web-based dashboards.
- Use of larger, diverse datasets (e.g., BraTS).
- Integration with clinical patient management systems.
- 3D MRI slice processing and tumor volume estimation.

## 👨‍💻 Team Contributors

- **Purnesh GC**  
- Bikram Panda  
- C Sai Krishna  
- Yuvraj V  

