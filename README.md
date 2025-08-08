# CNN-Based Multiclass Image Classification (Nature Scenes)

##  Overview
This project uses a **Convolutional Neural Network (CNN)** to classify natural scene images into **six categories**.  
The model is trained on a labeled dataset and is capable of recognizing various natural and urban landscapes with high accuracy.  

---

##  Classes
The model classifies images into the following **six categories**:

1. **Street** – Urban roads, pathways, and street views.  
2. **Glacier** – Snow-covered mountains, ice fields, and glaciers.  
3. **Mountain** – Rocky terrains, grassy hills, and high peaks.  
4. **Forest** – Dense vegetation, green landscapes, and woodland areas.  
5. **Sea** – Oceans, beaches, and coastal waters.  
6. **Buildings** – Man-made structures in both urban and rural settings.  

---

##  Dataset
- **Source**: [Natural Scenes Dataset](https://www.kaggle.com/datasets) *(Replace with your actual dataset link)*  
- **Total Images**: *Example: 15,000 images*  
- **Split**:
  - **Training**: 70%  
  - **Validation**: 15%  
  - **Test**: 15%  

---

##  Model Architecture
The CNN model is built using **TensorFlow/Keras** with the following layers:
- **Conv2D** layers for feature extraction  
- **MaxPooling2D** layers for downsampling  
- **Flatten** layer to convert feature maps into a 1D vector  
- **Dense** layers for classification  
- **Softmax** activation in the output layer for multiclass prediction  

---

##  Training Details
- **Loss Function**: `categorical_crossentropy`  
- **Optimizer**: `Adam`  
- **Epochs**: *Example: 25*  
- **Batch Size**: *Example: 32*  
- **Image Size**: *Example: 150x150 pixels*  

---

## Results
- **Training Accuracy**: *Example: 94%*  
- **Validation Accuracy**: *Example: 92%*  

**Sample Predictions:**  
![Sample Predictions](results/sample_predictions.png)  

---

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone <your_repo_link>
cd CNN_Multiclass_Classification
