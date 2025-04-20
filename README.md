# Dissecting breast cancer subtype-dependent aging acceleration and development of molecular and histology image-based aging clocks for the prediction of high-risk young-onset patients   

## 1. Background   
Breast cancer (BC) is the most common malignancy, causing millions of deaths worldwide. Significantly, the incidence rate of young-onset BC patients increased drastically over the last decade, and the young-onset BC patients were associated with higher recurrence rates and more advanced stages when diagnosed. However, the hidden mechanism driving the aggressiveness of young-onset BC patients is largely unknown.

## Major findings   
In our study, we comprehensively portrayed that the young-onset patients were significantly associated with better overall survival but poorer recurrence-free survival, higher rates of advanced tumor grade, and lymph node metastasis. Statistical results revealed significantly enriched Basal/HER2 subtypes in younger age groups. The multi-omics characterizations showed that young-onset BC patients were significantly enriched with more frequent TP53 mutation, whereas more PI3KAC was present in the late-onset group. Subsequently, we built a DNA methylation-based aging clock and revealed that young-onset patients had faster aging acceleration. Finally, a classifier using spatial organization features from histological images was developed and could accurately predict the aging acceleration-based BC subtypes. Our study comprehensively dissected the molecular features behind the aggressiveness of young-onset BC patients and could lead to the development of precision oncology for high-risk younger BC women.


## 3. Codes for data analysis   
* YOBC_Epidemiology.Rmd: Codes for breast cancer cohort survival and epidemiological analysis (related to Figure 2).
* YOBC_multi_omics.Rmd: Codes for the multi-omics analysis of four age groups (related to Figure 3).
* YOBC_aging_hallmark_analysis.Rmd: Codes for the collected 14 aging hallmarks with breast cancer subtypes (related to Figure 4).
* YOBC_methylation_aging_clock_prediction.Rmd: Codes for the gene-level DNA methylation-based aging clock prediction (related to Figure 5).
* YOBC_aging_acceleration_subtype.Rmd: Codes for identifying aging-acceleration-based subtypes using aging rate and gamma mixture model (related to Figure 6).
* YOBC_gamma_mixture_multiomics-heatmap.Rmd: Codes for the visualization of the heatmap of aging-acceleration-based subtypes (related to Figure 6).

## 4. Authors
Jiang Li, Xiangeng Wang, Yi Cao
