## Differentiation of Non-tuberculous Mycobacterial Pulmonary Disease and Pulmonary Tuberculosis in HIV/AIDS Patients Using a Multimodal Deep Learning Model Based on CT Imaging

### Abstract

Objective: To investigate the clinical value of a multimodal deep learning (DL) model based on computed tomography (CT) imaging for differentiating non-tuberculous mycobacterial pulmonary disease (NTM-PD) and pulmonary tuberculosis (PTB) in patients with human immunodeficiency virus infection/acquired immunodeficiency syndrome (HIV/AIDS).

Methods: We retrospectively collected the clinical data and chest CT images of patients with HIV/AIDS who had NTM-PD or PTB confirmed via etiological or pathological methods. Image preprocessing was performed using a strictly standardized workflow, and radiomics features were extracted with PyRadiomics. In addition, a DL model based on a pre-trained ResNet50 network was developed to extract deep features (DL2D). By combining selected key clinical features, we developed a clinical model, a radiomics model, a DL model, and a multimodal fusion model. Diagnostic performance, stability, and clinical utility were comprehensively evaluated using Receiver Operating Characteristic (ROC) curves, calibration curves, and Decision Curve Analysis (DCA). 

Results: In the test set, the multimodal fusion model achieved the best diagnostic performance, with an AUC of 0.909, a sensitivity of 0.783, and a specificity of 0.881, all of which were significantly better than those of the clinical, radiomics, or DL models. Statistical analysis showed that the NRI and IDI indices of the fusion model relative to the unimodal models were positive and statistically significant.

Conclusion: The multimodal model integrating clinical, radiomics, and DL features effectively combines multidimensional information. This model may serve as a powerful tool to support clinical decision-making.

Keywords: HIV/AIDS; Non-tuberculous Mycobacterial Pulmonary Disease; Pulmonary Tuberculosis; Deep Learning; Multimodal Fusion