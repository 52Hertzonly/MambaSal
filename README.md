# MambaSal: A Bio-Inspired Mamba-Driven Network for Visual Saliency Prediction

> 📌 **Status**: Manuscript under review  
> 🔒 **Code Availability**: The complete implementation will be released upon acceptance

---

## 📄 Overview

This repository is reserved for the official implementation of the paper:

> **MambaSal: A Bio-Inspired Mamba-Driven Network for Visual Saliency Prediction**

which is currently under review.

**MambaSal** proposes a biologically inspired neural architecture for visual saliency prediction by integrating **selective state space modeling (Mamba)** with human visual system (HVS)–motivated inductive biases. The proposed framework enables efficient long-range dependency modeling while maintaining a favorable accuracy–efficiency trade-off.

---

## 🔔 Code Availability Statement

To ensure research transparency, reproducibility, and fair peer review, we clarify that:

> **The complete source code will be made publicly available upon acceptance of the paper.**

The released package will include:

- Full model architecture and implementation
- Training and evaluation scripts
- Dataset loaders and preprocessing utilities
- Reproducible configuration files
- Pre-trained model weights
- Standard evaluation metrics for saliency prediction

This staged release policy follows common academic practice during the peer-review process.

---

## 🧠 Method Highlights

The proposed **MambaSal** framework is characterized by:

- **Linear-Complexity State Space Modeling**  
  Efficient long-range spatial dependency modeling using the Mamba architecture as an alternative to self-attention.

- **Bio-Inspired Visual Processing**  
  Explicit modeling of foveal–peripheral interaction through a Contrast–Mamba Synergy Module (CMSM).

- **Center-Biased Sequential Scanning**  
  A biologically inspired Archimedean spiral scanning strategy aligned with human visual attention bias.

- **End-to-End Supervised Learning**  
  Trained using standard saliency prediction datasets and evaluation protocols.

---

## 📊 Experimental Validation

The proposed method is evaluated on multiple widely used saliency benchmarks:

- SALICON  
- MIT300  
- MIT1003  
- CAT2000  
- TORONTO  

Experimental results demonstrate that **MambaSal achieves state-of-the-art or near state-of-the-art performance** while maintaining **significantly lower computational complexity** compared to Transformer-based saliency models.

Detailed quantitative and qualitative results will be provided in the paper and the accompanying code release.

---

## 📅 Planned Release

Upon acceptance of the manuscript, this repository will be updated with:

- Complete implementation code
- Pre-trained model weights
- Instructions for training and inference
- Reproducibility guidelines

Please stay tuned for the official release.

---


