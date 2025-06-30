# 🌿 Leveraging SWIN Transformer for Robust Cotton Leaf Disease Classification

**Sumaiya Khanam<sup>1,2</sup>, Mohammed Mohiuddin<sup>1,2</sup>, Deponker Sarker Depto<sup>3</sup>, and M.R.C. Mahdy<sup>3*</sup>**

<sup>1</sup>Department of Computer Science & Engineering, Premier University, Chattogram, Bangladesh  
<sup>2</sup>Mahdy Research Academy, Dhaka, Bangladesh  
<sup>3</sup>Department of Electrical & Computer Engineering, North South University, Dhaka, Bangladesh  

📧 Contact:  
{sumaiya.khanam01, mohiuddin2531}@gmail.com  
{deponker.sarker, mahdy.chowdhury}@northsouth.edu

---

## 📘 Overview

This repository provides the official implementation of deep learning models used in our journal paper titled:  
**"Leveraging SWIN Transformer for Robust Cotton Leaf Disease Classification."**  

We evaluate and compare the performance of several state-of-the-art architectures:

- ✅ Swin Transformer (Tiny variant)  
- ✅ DenseNet121  
- ✅ VGG16  
- ✅ MobileNetV2  
- ✅ Xception  

All models are trained and tested on the **SAR-CLD-2024** dataset, comprising over **7000 high-resolution cotton leaf images** across **7 classes**.

---

## 📁 Repository Structure

```
├── swin_transformer_tiny.ipynb     # Swin Transformer (Tiny) implementation
├── densenet121.ipynb               # DenseNet121 model
├── mobilenet.ipynb                 # MobileNetV2 model
├── vgg16.ipynb                     # VGG16 model
├── xception.ipynb                  # Xception model
└── README.md                       # Project documentation
```

---

## 🧪 Dataset Information

We used the **SAR-CLD-2024** dataset from:

📄 **"Cotton leaf disease image dataset (SAR-CLD): A dataset for machine learning based disease detection"**  
➡️ [ScienceDirect Article](https://www.sciencedirect.com/science/article/pii/S235234092400876X)  
➡️ [Mendeley Dataset Link](https://data.mendeley.com/datasets/b3jy2p6k8w/2)  

> 📌 Citation: *Yet to be published (2024)*

### 📂 Dataset Structure:
```
Original Dataset/
├── Bacterial Blight/
├── Curl Virus/
├── Herbicide Growth Damage/
├── Leaf Hopper Jassids/
├── Leaf Reddening/
├── Leaf Variegation/
└── Healthy Leaf/
```

---

## 🌿 Class Descriptions

- **Bacterial Blight**  
  Caused by *Xanthomonas citri pv. malvacearum*, it produces angular water-soaked lesions that darken over time. Affected leaves may necrotize and fall off, reducing photosynthesis and crop yield. Common in warm, humid environments.

- **Curl Virus (CLCuV)**  
  A Begomovirus transmitted by whiteflies. Symptoms include leaf curling, vein yellowing, puckering, and stunted growth. Severely affects fiber quality and yield.

- **Herbicide Growth Damage**  
  Results from incorrect herbicide application. Symptoms vary but may include yellowing, necrosis, and distorted leaves. Proper dosage and timing are crucial to avoid damage.

- **Leaf Hopper Jassids**  
  Small sap-sucking insects causing stippling, yellowing, and browning of leaves. Severe infestations can lead to curling and reduced vigor, affecting cotton output.

- **Leaf Reddening**  
  Characterized by reddish or purplish discoloration due to stress, often from nutrient deficiencies (e.g., phosphorus, potassium). Indicates disrupted chlorophyll production.

- **Leaf Variegation**  
  Irregular color patterns caused by mutations, viral infections, or nutrient imbalance. Reduces photosynthetic efficiency and plant productivity.

- **Healthy Leaf**  
  Uniform green color, intact structure, and absence of visible disease or pest damage. Critical for effective photosynthesis and plant development.

---

## 🧰 Installation

Install required packages using pip:

```bash
pip install -r requirements.txt
```

**Dependencies**:
- Python ≥ 3.8  
- PyTorch ≥ 1.12  
- torchvision  
- timm  
- numpy, pandas, matplotlib  
- scikit-learn  

---

## 🚀 How to Use

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/cotton-leaf-disease-classification.git
cd cotton-leaf-disease-classification
```

2. **Download Dataset**

Get the dataset from [Mendeley](https://data.mendeley.com/datasets/b3jy2p6k8w/2)  
Extract to match this format:

```
/path_to_dataset/Original Dataset/<Class Name>/*.jpg
```

Update the path in each notebook:
```python
DATASET_PATH = '/path_to_dataset/Original Dataset'
```

3. **Run Any Notebook**

Choose one of the `.ipynb` files and execute the cells. Grad-CAM, ROC curve, confusion matrix, and K-Fold CV are included.

---

## 📊 Model Features

- ✅ 5-Fold Cross-validation  
- ✅ ROC Curve, Confusion Matrix, and Classification Report  
- ✅ Grad-CAM heatmaps for visual interpretability  
- ✅ Train-validation-test split  
- ✅ Checkpoint saving of best model per fold  

---

## 💬 Contact

For questions or collaborations, feel free to reach out:

📨 sumaiya.khanam01@gmail.com  
📨 mohiuddin2531@gmail.com
