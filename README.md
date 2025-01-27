# 🚀 Mars Landmark Classifier  

## 📖 Overview  
The **Mars Landmark Classifier** is a system designed to enable efficient data transmission between space rovers and mission control. By incorporating an image compression pipeline and a classification model, this project addresses the unique challenges of space communication while preserving critical image data for scientific analysis.  

---

## ✨ Features  
- **Image Compression System**:  
  - Utilized a **CNN AutoEncoder** to compress 224x224 resolution images by **99%**, reducing them to 500-length latent vectors while maintaining image quality.  
- **Mars Landmark Classification**:  
  - Achieved **84.26% accuracy** on decoded feature vectors using a CNN-based classifier.  
- **Dataset Expansion**:  
  - Augmented the dataset with **2000 synthetic images** to address class imbalance, improving model robustness and performance.

---

## 🚀 Key Achievements  
- Validated the effectiveness of the compression system by achieving high classification accuracy on decoded vectors.  
- Significantly optimized data transmission for Mars missions, reducing communication overhead while preserving actionable data.  

---

## 🛠️ Tools and Technologies  
- **TensorFlow** for deep learning model development.  
- **Keras** for implementing the CNN AutoEncoder and classifier.  
- **Image Augmentation** techniques to expand the dataset and balance classes.

---

## 📝 How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/mars-landmark-classifier.git
   cd mars-landmark-classifier
