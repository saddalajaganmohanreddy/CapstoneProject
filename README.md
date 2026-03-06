# Underwater Pipeline Fault Detection Using DenseNet

## Authors
- **Sivanesh A** – Department of Computer Science and Engineering, Alliance University, Bangalore, India – asivanesh2003@gmail.com  
- **Pushpak T** – Department of Computer Science and Engineering, Alliance University, Bangalore, India – tpushpak099@gmail.com  
- **Saddala Jagan Mohan Reddy** – Department of Computer Science and Engineering, Alliance University, Bangalore, India – saddalajaganmohan@gmail.com  
- **Yeddula Harsha Vardhan Reddy** – Department of Computer Science and Engineering, Alliance University, Bangalore, India – yeddulaharsha1901@gmail.com  

## Project Overview
Underwater pipelines are prone to cracks and corrosion, which can cause environmental hazards and economic loss. This project proposes a **Deep Learning-based automated fault detection system** using **DenseNet** to classify pipeline images into three categories:

1. Normal Surface  
2. Cracks  
3. Corrosion  

The system reduces dependency on manual inspection, ensuring faster, safer, and more reliable monitoring.

## Modules
- **Image Acquisition Module** – Loads underwater pipeline images.  
- **Image Preprocessing & Enhancement Module** – Resizing, CLAHE, Bilateral Filtering, Sharpening.  
- **Feature Extraction (DenseNet) Module** – DenseNet with dense connections for feature reuse.  
- **Fault Classification Module** – Dense layers + Softmax for Crack, Corrosion, or Normal.  
- **Data Augmentation Module** – Rotation, shift, zoom, flip during training.  
- **Training & Evaluation Module** – Model training, computes accuracy/loss, and shows final results.  
- **Result Visualization Module** – Displays predictions, confidence, and training curves.  
- **Model Persistence & Inference Module** – Saves/loads `.h5` model and predicts on new images.  

## Results
- DenseNet achieved **99–100% validation accuracy** with minimal overfitting.  
- Accurately detects subtle cracks and corrosion under various underwater conditions.  
- Outperformed CNN, VGG, and ResNet architectures.  

## References
See `docs/references.md` for all research papers and sources.
