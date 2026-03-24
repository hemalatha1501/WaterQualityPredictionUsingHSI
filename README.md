# WaterQualityPredictionUsingHSI
# 🌊 DL-Driven Water Quality Prediction in Estuaries using Hyperspectral Signatures

## 📌 Overview
This project focuses on predicting and monitoring water quality in estuarine ecosystems using hyperspectral imagery and deep learning techniques. The system analyzes spectral characteristics of water bodies to classify them as **clean or contaminated** and provides a visual segmentation of affected regions.

---

## 🎯 Objectives
- Analyze hyperspectral satellite data for water quality assessment  
- Detect contaminated and clean water regions  
- Implement machine learning and deep learning models  
- Provide visual outputs such as segmentation maps and performance graphs  

---

## 🧠 Methodology
The project follows a step-by-step pipeline:

1. **Data Collection**  
   Hyperspectral and satellite images of estuarine regions  

2. **Preprocessing**  
   - Noise removal  
   - Normalization  
   - Dimensionality reduction  

3. **Feature Extraction**  
   - Extraction of spectral signatures  
   - Identification of patterns in wavelength bands  

4. **Model Implementation**  
   - Machine Learning: Random Forest, Isolation Forest  
   - Deep Learning: CNN (Convolutional Neural Network), UNet (U-Shaped Network), Attention-UNet  

5. **Prediction**  
   Classification of water as clean or contaminated  

6. **Segmentation Output**  
   Pixel-level detection of contaminated regions  

7. **Evaluation**  
   Metrics such as Accuracy, Precision, Recall, F1-score, and AUC  

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries:** OpenCV, NumPy, Matplotlib, Scikit-learn, TensorFlow/Keras  
- **Tools:** Jupyter Notebook / Google Colab  

---

## 📥 Input
- Hyperspectral or satellite image of water body  

## 📤 Output
- Classification result (Clean / Contaminated)  
- Segmentation map:
  - 🟢 Green → Clean regions  
  - 🔴 Red → Contaminated regions  
- Performance graphs (Accuracy, Loss, Confusion Matrix)  

---

## 🧪 Demo Implementation
A simplified prototype is implemented to demonstrate the workflow:

- Image preprocessing using OpenCV  
- Feature extraction using grayscale and edge detection  
- Simulated prediction logic  
- Segmentation output using color overlays  
- Graphs for model performance visualization  

---

## 📊 Sample Results
- CNN Accuracy: ~91%  
- UNet Accuracy: ~94%  
- Attention-UNet Accuracy: ~96%  

---

## 🌍 Applications
- Environmental monitoring  
- Pollution detection  
- Smart water management  
- Climate research  
- Government and environmental agencies  

---

## 🌱 SDG Mapping
- **SDG 6:** Clean Water and Sanitation  
- **SDG 14:** Life Below Water  

---

## ⚠️ Note
This project includes a **simplified prototype for demonstration purposes**.  
The actual system uses hyperspectral data and deep learning models like UNet and Attention-UNet for accurate segmentation.

---

## 🚀 Future Scope
- Real-time water quality monitoring system  
- Integration with IoT sensors  
- Advanced multi-class segmentation  
- Deployment as a web or mobile application  

---

## 👩‍💻 Author
Your Name  

---

## 📄 License
This project is for academic and research purposes.
