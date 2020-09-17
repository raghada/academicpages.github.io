---
title: "Age Regression from Brain MRI"
excerpt: "Predicting brain age given MRI brain data and comparing it to the chronological age of the patient is useful for detecting neurodegeneration and preventing cognitive decline. Using data from 652 healthy subjects we implemented three methods for age regression. The first approach uses the ratios of overall brain volume and the volumes of different brain tissues such as grey matter (GM), white matter (WM) and cerebrospinal fluid (CSF). The next two approaches use grey matter maps for PCA-based regression and CNN-based regression, respectively. The final testing shows that the CNN-based model performs better than the other considered models."
collection: portfolio
---

Predicting brain age given MRI brain data and comparing it to the chronological age of the patient is useful for detecting neurodegeneration and preventing cognitive decline. Using data from 652 healthy subjects we implemented three methods for age regression. The first approach uses the ratios of overall brain volume and the volumes of different brain tissues such as grey matter (GM), white matter (WM) and cerebrospinal fluid (CSF). The next two approaches use grey matter maps for PCA-based regression and CNN-based regression, respectively. The final testing shows that the CNN-based model performs better than the other considered models. <br>

<b> Source brain input images:</b> <br>
<img src="/images/brain_grey.png">
<br>
<b>Segmented brain:</b><br>
<img src="/images/brain_segmented.png"><br>
<b>Best model results:</b><br>
<img src="/images/best_model_mri.png">



