# 🧠 TF2 Custom Object Detection Pipeline - TFLite Compatible (Colab Notebook)

This repository provides a complete pipeline to train a **TensorFlow 2 Object Detection** model and convert it into a **TFLite model** using **Google Colab**. It covers everything from dataset setup to model quantization and testing.

---

## 📁 Notebook: `TF2_CUSTOM_OBJECT_DETECTION_COMPLETE_RUN.ipynb`


![Demo](assets\rbox.gif)

### ✅ Features
- Python environment setup for TensorFlow 2.x
- Image dataset loading from Google Drive
- Pre-requisites installation and TensorFlow Object Detection API setup
- Custom training configuration
- Model training and evaluation
- Export to TFLite (quantized) model format
- Model testing and mAP (mean Average Precision) calculation
- Save checkpoints and final models to Google Drive

---

## 🔧 Steps Overview

### 🧩 Setup
1. **Python Version Update**  
2. **Mount Google Drive to Colab**

### 📦 Data & Dependencies
3. **Import Image Dataset**  
4. **Install All Required Packages**  
5. **Set TFRecord Paths**  
6. **Model Configuration File Setup**

### 🔁 Training
7. **Set Training Parameters**  
8. **Train the Model**

### 📤 Export
9. **Convert to TensorFlow SavedModel Format**  
10. **Convert to Quantized TFLite Model**  
11. **Write Metadata for TFLite Model**

### ✅ Testing & Evaluation
12. **Test the TFLite Model**  
13. **Calculate mAP**

### 💾 Save Outputs
- Save **Checkpoints** to Drive  
- Save **Final Trained Model** Folder  

---

## 🛠️ Handy Shell Commands

| Task                     | Command |
|--------------------------|---------|
| Create new directory     | `!mkdir 'path_to_new_dir'` |
| Copy directory securely  | `!scp -r 'source_path' 'destination_path'` |
| Unzip directory          | `!unzip 'file.zip' -d 'target_path'` |
| Zip a directory          | `!zip -r 'output.zip' 'folder_to_zip'` |

---

## 📌 Requirements
- Google Account (to access Google Colab & Drive)
- Labelled image dataset in Pascal VOC format or TFRecord
- Basic understanding of TensorFlow 2.x

---

## 📎 Output
- Trained `.tflite` model
- Quantized version with metadata
- Evaluation metrics (e.g. mAP)

---

## 📍 License
This notebook is shared under the [MIT License](LICENSE). Feel free to fork and adapt it for your use cases!
