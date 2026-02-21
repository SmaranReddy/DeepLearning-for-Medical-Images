# Medical Image Segmentation and Analysis

**Name:** A. Smaran Reddy  
**Roll Number:** CS23B1011  
**Branch:** Computer Science  

---

## Project Overview
This notebook is part of a combined medical image segmentation project focusing on different biomedical imaging modalities. Classical image processing techniques such as thresholding, morphological operations, distance transforms, and watershed segmentation are used to extract meaningful biological structures.

---

## Order of Experiments

### 1. Brain MRI Tumor Segmentation (Otsu vs Sauvola)
**Notebook:** `brain_mri_otsu_sauvola.ipynb`

- Compared global (Otsu) and adaptive (Sauvola) thresholding methods
- Observed that adaptive thresholding performs better under non-uniform illumination
- Morphological operations were applied for refinement

---

### 2. White Blood Cell Segmentation
**Notebook:** `WhiteBloodCells_cs23b1011.ipynb`

- Segmented white blood cells from blood smear images
- Used thresholding, color analysis, and morphological filtering
- Successfully isolated WBCs from background and red blood cells

---

### 3. Retina Blood Vessel Extraction
**Notebook:** `RetinaVesselExtraction_cs23b1011.ipynb`

- Extracted retinal blood vessels using green channel enhancement
- Applied adaptive thresholding and morphological operations
- Generated clear vessel maps useful for retinal disease analysis

---

### 4. Cell Nuclei Segmentation
**Notebook:** `CellNuclei_cs23b1011.ipynb`

- Segmented individual cell nuclei from microscopy images
- Used Otsu thresholding, distance transform, and watershed algorithm
- Marker-controlled watershed successfully separated overlapping nuclei

---

## Conclusion
These experiments demonstrate that classical image processing techniques, when combined with proper preprocessing and marker-based methods, can effectively segment complex medical images. Adaptive and marker-based approaches consistently outperform naive global methods in real-world biomedical data.
