# CS747-Project
GMU CS 747 Deep Learning

Team 3

Project Title: Impressionist Imagery with CycleGAN: Unpaired Image Translation for Monet-Style Generation

Track: Kaggle Competition

Competition Link: https://www.kaggle.com/c/gan-getting-started

Team Members:
1. Bhadri Prabhav Kuruganti
2. Indra Anuraag Gade
3. Rohit Reddy Bheemireddy

# Impressionist Imagery with CycleGAN  
### Unpaired image-to-image translation for generating Monet-style artwork

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-1.12+-red.svg)
![CycleGAN](https://img.shields.io/badge/Model-CycleGAN-orange.svg)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Overview

This repository contains the code, methodology, and final report for our project  
**“Impressionist Imagery with CycleGAN: Unpaired Image Translation for Monet-Style Generation,”**  
completed for **GMU CS 747 — Deep Learning - Fall 2024**.

The goal of the project is to generate **Monet-inspired Impressionist images** from real photographs using **CycleGAN**, trained on unpaired datasets of Monet paintings and natural images.

This repository serves as a **research archive**: the complete code and report are preserved, while trained weights and large-scale outputs are not included due to compute constraints.

---

## 🧠 Method Summary

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

## 🖼️ Architecture

> **Add architecture diagram here**  
> *(insert image)*

---

## 🏞️ Sample Outputs

> **Add input → Monet output image grids here**  
> *(insert images)*

---

## ⚠️ Reproducibility Notes

- Trained model weights **are not available**  
- ≈7000 generated images for Kaggle submission are **not included**  
- Final training and inference were performed on **university cluster + Kaggle GPU**  
- This repository documents the methodology and code rather than a fully runnable pipeline

---

## 👥 Team Members

- **Bhadri Prabhav Kuruganti**
- **Indra Anuraag Gade** 
- **Rohit Reddy Bheemireddy** 

---

## 📄 License

Released under the **MIT License** for research and educational use.

---
