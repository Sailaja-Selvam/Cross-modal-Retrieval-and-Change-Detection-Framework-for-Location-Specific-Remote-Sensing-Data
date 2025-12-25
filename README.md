# Cross-modal-Retrieval-and-Change-Detection-System-for-Location-Specific-Remote-Sensing-Data

Retrieving satellite images using free-form natural language is a challenging and underdeveloped area in remote sensing.
Traditional cross-modal retrieval approaches often:
   - Fail to capture the semantic richness of textual descriptions
   - Struggle with accurate alignment of visual and textual modalities, particularly in remote sensing
Complexity of Remote Sensing Data:
- Satellite imagery includes diverse landforms, heterogeneous objects, and complex spatial layouts
Effective understanding requires:
   - High-level contextual 
   - Fine-grained spatial relationships

## DATA COLLECTION
1. Regional Specificity Existing remote sensing datasets (e.g., RSICD, RSCID) lack fine-grained coverage of Tamil Nadu; no publicly available corpus provided village–taluk-level imagery.
2. Custom Data Collection (Google Earth Pro): High-resolution, orthographic imagery was programmatically captured using PyAutoGUI, ensuring consistent framing and reproducibility across administrative units.
3. Temporal Control (Explicit Year/Season Selection): Unlike existing datasets with limited or inferred temporal ranges, the proposed dataset enforces explicit month/year capture (e.g., May 2023), reducing seasonal variance and enabling temporal change detection.
4. Novel Contribution: Provides the Tamil Nadu–specific satellite image–text dataset, combining high-resolution imagery, administrative metadata, and temporal consistency for downstream multimodal retrieval and analysis.

## Collected Images from 2014 to 2014 in Chennai District based on taluk and localities.Each year has 119 images 

## ARCHITECTURE:

 <img width="755" height="399" alt="image" src="https://github.com/user-attachments/assets/530b001d-281f-4e91-adde-371de2abfacf" />

 ## Segmentation Outputs :
 
 <img width="688" height="257" alt="image" src="https://github.com/user-attachments/assets/864c47d8-2799-487a-80c4-829991f53730" />

## System Retrieval Output :
<img width="749" height="406" alt="image" src="https://github.com/user-attachments/assets/50b4b2a6-2332-4b6b-866a-12c564963b72" />

