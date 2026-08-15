# Accuracy Assessment of Land Cover Classification in Trincomalee Bay Region

![Accuracy Assessment](https://img.shields.io/badge/Accuracy-78.79%25-brightgreen)
![Kappa Statistic](https://img.shields.io/badge/Kappa_Index-0.739-blue)
![Domain](https://img.shields.io/badge/Domain-Remote_Sensing_%26_GIS-orange)

## 📌 Project Overview
This study evaluates the accuracy of **Supervised Land Cover Classification** using **Sentinel-2 Multi-Spectral Satellite Imagery** for the **Trincomalee Bay region** in northeastern Sri Lanka[cite: 1]. The primary objective is to evaluate classification performance across eight distinct land cover categories using a stratified random sampling technique and confusion matrix validation[cite: 1].

* **Author:** E.A.D.C. Edirisinghe [cite: 1]
* **Institution:** Department of Geography, University of Peradeniya[cite: 1]

---

## 🔑 Key Metrics & Performance

| Performance Metric | Result | Interpretation |
| :--- | :--- | :--- |
| **Overall Accuracy** | **78.79%** | 130 out of 165 validation points correctly classified[cite: 1] |
| **Kappa Coefficient ($\kappa$)** | **0.739** | Substantial/Strong agreement taking chance into account[cite: 1] |
| **Sample Points** | **165 Points** | Distributed across 8 classes via Stratified Random Sampling[cite: 1] |

---

## 🗺️ Land Cover Classes & Accuracy Breakdown

Supervised classification was performed to classify the region into eight land cover types[cite: 1]. High spectral distinction classes (e.g., Water, Vegetation) yielded superior accuracy, whereas spectrally similar classes (e.g., Developed Area, Bare Earth) presented higher confusion[cite: 1].

| Land Cover Class | User's Accuracy (%) | Producer's Accuracy (%) | Performance Level[cite: 1] |
| :--- | :---: | :---: | :--- |
| **Water** | 100.00% | 90.91% | Very High[cite: 1] |
| **Vegetation** | 100.00% | 84.38% | High[cite: 1] |
| **Bare Earth** | 81.82% | 60.00% | Moderate[cite: 1] |
| **Cultivated Area** | 73.91% | 70.83% | Moderate[cite: 1] |
| **Herbaceous** | 70.00% | 87.50% | Moderate[cite: 1] |
| **Wetland** | 40.00% | 100.00% | Low (High Omission/Commission)[cite: 1] |
| **Shoreline** | 40.00% | 100.00% | Low[cite: 1] |
| **Developed Area** | 23.08% | 37.50% | Low (High spectral confusion)[cite: 1] |

---

## 🛠️ Methodology & Tools

1. **Data Source:** Sentinel-2 Multi-Spectral Imagery acquired via European Space Agency (ESA) Copernicus Open Access Hub[cite: 1].
2. **Pre-processing:** Cloud screening and atmospheric corrections applied[cite: 1].
3. **Training Samples:** 30 representative training sample points selected per class[cite: 1].
4. **Validation:** Stratified random generation of 165 reference points verified against high-resolution imagery and ground truth data[cite: 1].
5. **Accuracy Assessment:** Computation of Error Matrix, Overall Accuracy, User's Accuracy, Producer's Accuracy, and Kappa Index ($\kappa$)[cite: 1].

---

## 💡 Future Recommendations
To enhance classification performance for spectral overlapping classes (e.g., Developed vs. Bare Earth)[cite: 1]:
* Integrate spectral indices such as **NDVI** (Normalized Difference Vegetation Index) and **NDWI** (Normalized Difference Water Index)[cite: 1].
* Apply multi-temporal analysis to track phenological changes[cite: 1].
* Incorporate spatial texture features or elevation datasets (DEM/LiDAR)[cite: 1].
