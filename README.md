# ML Repository - MediSight

This repository contains the machine learning model and dataset used in the **MediSight mobile application**. MediSight leverages machine learning to assist users in identifying minor wound types accurately and efficiently.

---

## **Repository Structure**

### **1. Dataset**
The `dataset/` folder contains the labeled dataset used for training the minor wound classification model. It includes five categories:  
- `abrasions/` - Abrasions (minor scratches or scrapes)  
- `bruises/` - Bruises (minor discolored skin caused by bleeding under the skin)  
- `burns/` - Burns (minor tissue damage caused by heat, chemicals, or radiation)  
- `cut/` - Cuts (minor incisions or lacerations on the skin)  
- `normal/` - Normal skin (no wounds or abnormalities)  

### **2. Notebook File**
- **`wounds_notebook.ipynb`**  
   This notebook contains the code used for training the minor wound classification model. It includes data preprocessing, model architecture, training process, evaluation metrics, and code to convert model.

### **3. Model Files**
- **`wounds_model_fix.h5`**  
  The saved model in **HDF5 format** for reusability and further training.  

- **`wounds_model_fix.tflite`**  
  The **TensorFlow Lite model** optimized for deployment in the MediSight mobile application.

### **4. Class Label File**
- **`class_label_model.txt`**  
  This file contains the class labels in the order used by the trained model, ensuring consistent mapping between predictions and wound categories.
