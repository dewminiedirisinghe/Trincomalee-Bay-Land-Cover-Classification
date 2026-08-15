# Accuracy Assessment of Land Cover Classification in Trincomalee Bay Region

![Accuracy Assessment](https://img.shields.io/badge/Accuracy-78.79%25-brightgreen)
![Kappa Statistic](https://img.shields.io/badge/Kappa_Index-0.739-blue)
![Domain](https://img.shields.io/badge/Domain-Remote_Sensing_%26_GIS-orange)

## 📌 Project Overview
This study evaluates the accuracy of **Supervised Land Cover Classification** using **Sentinel-2 Multi-Spectral Satellite Imagery** for the **Trincomalee Bay region** in northeastern Sri Lanka. The primary objective is to evaluate classification performance across eight distinct land cover categories using a stratified random sampling technique and confusion matrix validation.

* **Author:** E.A.D.C. Edirisinghe 
* **Institution:** Department of Geography, University of Peradeniya.
---

## 🔑 Key Metrics & Performance

| Performance Metric | Result | Interpretation |
| :--- | :--- | :--- |
| **Overall Accuracy** | **78.79%** | 130 out of 165 validation points correctly classified |
| **Kappa Coefficient ($\kappa$)** | **0.739** | Substantial/Strong agreement taking chance into account |
| **Sample Points** | **165 Points** | Distributed across 8 classes via Stratified Random Sampling |

---

## 🗺️ Land Cover Classes & Accuracy Breakdown

Supervised classification was performed to classify the region into eight land cover types. High spectral distinction classes (e.g., Water, Vegetation) yielded superior accuracy, whereas spectrally similar classes (e.g., Developed Area, Bare Earth) presented higher confusion.

| Land Cover Class | User's Accuracy (%) | Producer's Accuracy (%) | Performance Level |
| :--- | :---: | :---: | :--- |
| **Water** | 100.00% | 90.91% | Very High |
| **Vegetation** | 100.00% | 84.38% | High |
| **Bare Earth** | 81.82% | 60.00% | Moderate |
| **Cultivated Area** | 73.91% | 70.83% | Moderate |
| **Herbaceous** | 70.00% | 87.50% | Moderate |
| **Wetland** | 40.00% | 100.00% | Low (High Omission/Commission) |
| **Shoreline** | 40.00% | 100.00% | Low |
| **Developed Area** | 23.08% | 37.50% | Low (High spectral confusion) |

---

## 🛠️ Methodology & Tools

1. **Data Source:** Sentinel-2 Multi-Spectral Imagery acquired via European Space Agency (ESA) Copernicus Open Access Hub.
2. **Pre-processing:** Cloud screening and atmospheric corrections applied.
3. **Training Samples:** 30 representative training sample points selected per class.
4. **Validation:** Stratified random generation of 165 reference points verified against high-resolution imagery and ground truth data.
5. **Accuracy Assessment:** Computation of Error Matrix, Overall Accuracy, User's Accuracy, Producer's Accuracy, and Kappa Index ($\kappa$).

---

## 💡 Future Recommendations
To enhance classification performance for spectral overlapping classes (e.g., Developed vs. Bare Earth):
* Integrate spectral indices such as **NDVI** (Normalized Difference Vegetation Index) and **NDWI** (Normalized Difference Water Index).
* Apply multi-temporal analysis to track phenological changes.
* Incorporate spatial texture features or elevation datasets (DEM/LiDAR).
