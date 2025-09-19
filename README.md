# 🌊 Water Segmentation using U-Net

## 🎯 Objective
Build a **deep learning model** for accurate segmentation of water bodies from **multispectral and optical data**.  
---

## 🗂 Key Components
- **Data Prep**: Load 12-channel multispectral images and masks, normalize [0,1], split train/val.  
- **Visualization**: Inspect spectral bands, RGB composite, and masks.  
- **Model**: U-Net architecture for pixel-level segmentation.  
- **Training**: Adam optimizer, binary_crossentropy loss, 25 epochs, batch size 16.  

---

## 📊 Evaluation
Metrics for **water class**:  
- IoU ✅  
- Precision 🎯  
- Recall 📈  
- F1-Score ⚖️  

---

## 🏃 How to Run
1. Open a **Kaggle Notebook**.  
2. Add the **water-segmentation dataset**.  
3. Paste `water_segmentation_notebook.py` code.  
4. Run cells sequentially (handles loading, training, visualization).  

---

## 📦 Dependencies
`os`, `glob`, `numpy`, `tensorflow`, `scikit-learn`, `Pillow`, `matplotlib`

---

✅ End-to-end workflow from raw multispectral images to **evaluated water segmentation masks**.
