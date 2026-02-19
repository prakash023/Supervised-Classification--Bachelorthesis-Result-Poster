# Sentinel-2 Land Cover Classification using Random Forest

## Overview
This project was developed as part of my Bachelor thesis Poster presentation.
The objective was to classify Sentinel-2 satellite imagery using a supervised machine learning approach based on the Random Forest algorithm.

Five land cover classes were generated and validated using a confusion matrix and accuracy assessment.

---

## Data

- Satellite data: Sentinel-2 (10 m spatial resolution)
- Reference dataset: CORINE Land Cover 2018
- Study area: [Insert study area name if you want]

---

## Methodology

1. Image preprocessing
2. Creation of training samples (stratified sampling)
3. Supervised classification using Random Forest
4. Accuracy assessment using confusion matrix
5. Comparison with CORINE Land Cover 2018 dataset

The classification was performed in ERDAS Imagine using the Spatial Modeler.

---

## Classes

The following land cover classes were defined:

- Agriculture
- Forest
- Grassland
- Urban
- Water

---

## Results

- Overall Accuracy: **76%**
- Producer’s and User’s accuracy were calculated for each class
- Forest and Water showed strong classification performance
- Agriculture and Grassland showed moderate spectral confusion

The comparison with CORINE Land Cover resulted in lower agreement (~55%) due to differences in spatial resolution and generalization level.

---

## Key Learnings

- The quality and distribution of training samples strongly influence classification accuracy.
- Spectral similarity between vegetation classes can reduce separability.
- Dataset resolution differences significantly affect validation results.

---

## Tools & Software

- ERDAS Imagine (Spatial Modeler)
- 
- CORINE Land Cover dataset
- Sentinel-2 imagery

##Result image:
- <img width="212" height="246" alt="class_" src="https://github.com/user-attachments/assets/26634e71-033d-490b-8e3c-f12406e1ef82" />


--
