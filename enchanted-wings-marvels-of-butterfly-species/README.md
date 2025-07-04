# 🦋 Enchanted Wings: Marvels of Butterfly Species

A deep learning project that classifies butterfly species using MobileNetV2 architecture, trained on a custom dataset.

---

## 📌 Project Objective

To build a machine learning model that classifies different species of butterflies based on image input using transfer learning.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas / Seaborn
- Scikit-learn
- Google Colab (for training)
- Git & GitHub

---

## 🗃️ Dataset

The dataset contains:
- Butterfly images from multiple species
- Train and test folders
- `Training_set.csv` and `Testing_set.csv` files for labels

Due to size limits, dataset is not included here.  
➡️ [Link to download from Google Drive](#) *(replace this with your actual Drive link)*


--### 🗂️ Dataset Download
Download the ZIP file containing the butterfly species dataset (train/test folders and CSV files):  
👉 [Download Dataset](https://drive.google.com/file/d/14iGl-aEfr7NOw24Ac962J_IprESEYVGl/view?usp=sharing)


---## 📂 Resources

### 📽️ Project Demo Video
Watch the complete demo showing dataset, model training, predictions, and GitHub structure:  
👉 [Watch the Demo Video](https://drive.google.com/file/d/1JRyLvZWfCLFpKOXLvKNtULIrYOBIbqS5/view?usp=sharing)

---



## 📊 Data Preparation

- Visualized class distribution using Seaborn
- Displayed sample images
- Stored screenshot in `/screenshots/data_distribution.png`

---

## 🧠 Model Architecture

- **Base Model**: MobileNetV2 (pretrained on ImageNet)
- **Custom Layers**: GlobalAveragePooling → Dropout → Dense → Softmax
- **Loss**: Sparse Categorical Crossentropy
- **Optimizer**: Adam

---

## 🚀 How to Run

### 1. Install Dependencies

```bash
pip install -r requirements.txt
