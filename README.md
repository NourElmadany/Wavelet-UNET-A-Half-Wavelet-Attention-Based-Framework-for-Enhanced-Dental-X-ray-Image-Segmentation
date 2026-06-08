# Wavelet-UNET: A Half-Wavelet Attention-Based Framework for Enhanced Dental X-ray Image Segmentation

[![Paper Under Review](https://img.shields.io/badge/Paper-Under_Review-yellow.svg)]()
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

> **Note:** This repository contains the official PyTorch implementation for the paper **"Wavelet-UNET: A Half-Wavelet Attention-Based Framework for Enhanced Dental X-ray Image Segmentation"** (Currently under review). 

---

## 📖 Overview

Dental X-ray image segmentation is a critical step in automated computer-aided diagnosis (CAD) systems in dentistry. However, varying contrast, noise, and complex tooth structures pose significant challenges. 

**Wavelet-UNET** introduces a novel **Half-Wavelet Attention Mechanism** integrated into a UNET architecture. By leveraging the frequency and spatial domain characteristics of discrete wavelet transforms, our framework effectively captures high-frequency edge details (like tooth boundaries and roots) while maintaining robust global feature representations.

### ✨ Key Features
* **Half-Wavelet Attention Block:** Efficiently focuses on critical spatial features by separating frequency sub-bands.
* **Enhanced Edge Preservation:** Specifically designed to delineate complex dental structures with high precision.


---

## 🏗️ Architecture

*(Replace the URL below with a link to your actual architecture diagram hosted in your repo, e.g., `assets/architecture.png`)*

![Wavelet-UNET Architecture](https://via.placeholder.com/800x400?text=Insert+Wavelet-UNET+Architecture+Diagram+Here)

*Figure 1: Overall architecture of the proposed Wavelet-UNET framework, highlighting the integration of the Half-Wavelet Attention blocks.*

---

## 🛠️ Installation & Requirements

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/Wavelet-UNET.git](https://github.com/YourUsername/Wavelet-UNET.git)
   cd Wavelet-UNET
