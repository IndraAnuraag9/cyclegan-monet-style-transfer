# Impressionist Imagery with CycleGAN  
### Unpaired image-to-image translation for generating Monet-style artwork

## Overview

This repository contains the code, methodology, and final report for our project **“Impressionist Imagery with CycleGAN: Unpaired Image Translation for Monet-Style Generation,”** completed for **GMU CS 747 — Deep Learning — Fall 2024**.

The goal of the project is to generate **Monet-inspired Impressionist images** from real photographs using **CycleGAN**, trained on unpaired datasets of Monet paintings and natural images.

This repository serves as a **research archive**: the complete code and report are preserved, while trained weights and large-scale outputs are not included due to compute constraints.

Kaggle Competition Link: https://www.kaggle.com/c/gan-getting-started

---

## Method Summary

We implemented and iteratively improved a CycleGAN-based system for artistic style transfer.  
Three primary versions were built:

### **V1 — Baseline CycleGAN**
- Standard architecture  
- Frequent mode collapse and unstable training  

### **V2 — Stability Enhancements**
- Color consistency loss  
- Learning rate and batch size tuning  

### **V3 — Final Model**
- Style loss using VGG features  
- Residual blocks with grouped convolutions  
- Histogram equalization  
- Significantly improved texture and stylistic fidelity  
- Achieved **MiFID: 73.59**

---

## Architecture

> <img width="483" height="464" alt="image" src="https://github.com/user-attachments/assets/f997cda4-ecf6-4ffa-832d-2b376c8cdb57" />

---

## Sample Outputs

> **V1**  
> <img width="465" height="247" alt="image" src="https://github.com/user-attachments/assets/49167f61-13e2-44ee-b072-bfba23723ef9" />

> **V2**  
> <img width="460" height="227" alt="image" src="https://github.com/user-attachments/assets/202d5f03-93f7-4923-9963-59ed3936d0d5" />

> **V3**  
> <img width="459" height="225" alt="image" src="https://github.com/user-attachments/assets/a4ed7b36-7464-4d8c-849b-2d7b33e29e06" />

> **More Monet Style Generated Images**
> <img width="451" height="421" alt="image" src="https://github.com/user-attachments/assets/64b208e2-5da2-429d-a5e1-711940d599e3" />

---

## Reproducibility Notes

- Trained model weights **are not available**  
- ≈7000 generated images for Kaggle submission are **not included**  
- Final training and inference were performed on **university cluster + Kaggle GPU**  
- This repository documents the methodology and code rather than a fully runnable pipeline

---

## Team Members

- **Bhadri Prabhav Kuruganti**
- **Indra Anuraag Gade** 
- **Rohit Reddy Bheemireddy** 

---

## License

Released under the **MIT License** for research and educational use.

---
