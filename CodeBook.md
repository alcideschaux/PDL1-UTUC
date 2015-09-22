---
title: Codebook
output: html_document
---

Variable | Label | Description
:--- | :--- | :---
TMAID | TMA ID | ID from 1 to 99
PDL1_tumor | Percentage of PDL1-positive tumor cells | 0--100%
PDL1_tumor_location | Location of PDL1 in tumor | Cytoplasmic/Membraneous/Cytoplasmic & Membranous
PDL1_H | PDL1 H-score in tumor | 0--300 points
PDL1_stroma | Percentage of PDL1-positive inflammatory cells in stroma | 0--100 %
PDL1_stroma_location | Location of inflammation in relationship to tumor | Adherent to tumor/Away from tumor
Granulomas | Presence of granulomas | No/Yes
PDL1_granulomas | PDL1 positivity in granulomas | No/Yes
Host_response | Inflammatory reaction in tumor and tumor-related stroma | No inflammatory cells/Rare inflammatory cells/Lymphoid aggregates/Intense inflammation
FOXP3_lymph_tumor | Intratumoral count of FOXP3 positive lymphocytes per high-power field in the most crowded area | Real numbers
FOXP3_lymph_stroma | Count of FOXP3 positive lymphocytes in stroma per high-power field | Real numbers
FOXP3_lymph_intensity | Intensity of FOXP3 staining in lymphocytes | No staining/Weak staining/Moderate staining/Strong staining
FOXP3_tumor | Count of FOXP3-positive tumor cells | Real numbers
FOXP3_tumor_intensity | Intensity of FOXP3 staining in tumor cells | No staining/Weak staining/Moderate staining/Strong staining
FOXP3_tumor_positive | Percentage of FOXP3-positive tumor cells | 0--100%
CD8_tumor | Intratumoral count of CD8-positive cells per high-power field in the most intensively inflamed area | Real numbers
CD8_Ki67_tumor | Intratumoral count of double CD8 and Ki67 positive cells per high-power field in the most intensively inflamed areas | Real numbers
CD8_stroma | Count of stromal CD8-positive cells per high-power field in the most crowded areas | Real numbers
CD8_Ki67_stroma | Count of double stromal CD8 and Ki67 positive cells per high-power field in the most crowded areas | Real numbers
Ki67_tumor | Percentage of Ki67-positive tumor cells | 0-100%
