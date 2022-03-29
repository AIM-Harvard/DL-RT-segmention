### Clinical Validation of Deep Learning Algorithms for Lung Cancer Radiotherapy Targeting

This repository contains output data for the study titled "Clinical Validation of Deep Learning Algorithms for Lung Cancer Radiotherapy Targeting".
TODO: Add link to study + citation when published.

  
#### Contents

For each of the 6 public datasets on which validation was performed (RTOG-0617, NSCLC-radiogenomics, RIDER, Thorax phantom, Lung-PET-CT-Dx, Multi-delineation), we include the following here:

- AI-generated segmentations in binary 3D files (.nrrd) with sizes and pixel spacing that match the corresponding publicly available CT images on the TCIA database. As such, they could be used to benchmark against other models. These are provided for both assisted and automated models.

- Tabular data (.csv) showing results where every row represents a CT image while columns represent segmentation metrics between AI-generated and ground truth segmentations (all metrics used in the study). These can be used to reproduce plots, figures, and statistics. These are also provided for both assisted and automated models.  

For access to the publicly available CT imaging datasets, use the following links:

|dataset|link|
|----|----|  
|RTOG-0617|[link](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=33948334)|
|NSCLC-radiogenomics|[link](https://wiki.cancerimagingarchive.net/display/Public/NSCLC+Radiogenomics#6a3175f88bf2483c874777cadd372e8f)|
|RIDER|[link](https://wiki.cancerimagingarchive.net/display/Public/RIDER+Lung+CT)|
|Thorax phantom|[link](https://wiki.cancerimagingarchive.net/display/Public/Lung+Phantom)|
|Lung-PET-CT-Dx|[link](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216)|
|Multi-delineation|[link](https://wiki.cancerimagingarchive.net/display/Public/NSCLC-Radiomics-Interobserver1)|
