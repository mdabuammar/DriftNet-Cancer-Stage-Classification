# DriftNet-Cancer-Stage-Classification
Deep learning model for predicting cancer stage (I/II/III) using DNA methylation and clinical features across multiple cancer types.

# DriftNet: Pan-Cancer Stage Classification using DNA Methylation and Contrastive Learning

This repository contains the code and notebooks for the paper:

**"DriftNet: Contrastive Learning for Pan-Cancer Stage Classification"**

The goal of this project is to predict cancer stage (Stage I, II, or III) using DNA methylation data and clinical features. DriftNet combines deep learning, contrastive learning, and data compression for accurate stage prediction across different cancer types.

---

## 🧪 Project Files

- `1_Driftnet.ipynb`  
  Main notebook: trains the DriftNet model using VAE + contrastive learning and dual-branch neural network.

- `Data_Preprocessing.ipynb`  
  Prepares the DNA methylation and clinical data (TCGA) and filters valid Stage I–III cases.

- `driftnet-comparing-full-features.ipynb`  
  Compares performance between full (raw) methylation features and VAE-compressed features.

---
## 🤝 Contact

For questions or collaboration, please contact:  
**Md Abu Ammar**  
Email: [mdabuammar1@gmail.com]
