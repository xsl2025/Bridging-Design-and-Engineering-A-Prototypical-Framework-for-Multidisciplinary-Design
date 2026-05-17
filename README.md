We employed two gradient-boosting frameworks as baselines: XGBoost and LightGBM. The comparative results demonstrate that LightGBM consistently outperforms XGBoost across all architectural performance dimensions, yielding improvements of 2.28%, 5.17%, and 1.70% for Energy Use Intensity (EUI), RDS and Functional Suitability, respectively. 
The comparative analysis reveals a distinct performance-enhancement hierarchy across the three evaluation dimensions (EUI, RDS, and Functionality). While our proposed deep learning framework consistently outperforms the gradient-boosting baselines (XGBoost and LightGBM), the magnitude of this improvement varies significantly by metric.
The marginal gain in Energy Use Intensity (EUI) prediction suggests that the energy performance is primarily dominated by building parameters (e.g., WWR, U-values) already captured by classical parametric models, leaving limited 'spatial-morphological' headroom for enhancement. Conversely, the substantial improvements in RDS (18.7%) and Functional Suitability (7.99%) underscore the critical role of spatial-topological intelligence. Unlike tabular parameters, our visual-based deep learning framework successfully extracts complex latent features—such as mutual self-shading, non-linear aperture-to-core adjacencies, and the homogeneity of open-plan layouts—which are inherently difficult to encode within the rigid feature sets of tabular machine learning models.
By introducing the Expert Prototype as a high-quality prior, this framework leverages a structured-parametric logic (Spatial Structure + Parameters) to achieve higher interpretability and better prediction.

<img width="945" height="976" alt="image" src="https://github.com/user-attachments/assets/726467ef-bc3c-40b0-96c8-d1a1f89b3102" />
<img width="559" height="478" alt="image" src="https://github.com/user-attachments/assets/62cf6ee0-65c3-4d3d-b90a-87c506122592" />
<img width="945" height="945" alt="image" src="https://github.com/user-attachments/assets/88246e27-5936-467e-b672-f8723f021aa2" />

## Download
Large gh files are hosted on Google Drive:
https://drive.google.com/file/d/1HWkdBYXkPRhMe_Ul_l2LK9fJBox0oY9i/view?usp=drive_link
Copyright © 2026 Xusheng Li. All rights reserved.
