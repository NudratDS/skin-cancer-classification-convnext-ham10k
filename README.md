<div align="center">

![Skin Cancer Classification](https://img.shields.io/badge/Skin%20Cancer-Classification-red?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-94%25-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

---

<div align="center">

# Skin Cancer Classification using ConvNextBase

Every year, over 1.5 million people are diagnosed with skin cancer.
Most of them could have been saved — if caught early enough.

This project exists because early detection should not depend on where you live or whether you can afford a dermatologist.

</div>

---

## The Problem

Dermatologists are overwhelmed. Appointment waitlists stretch weeks. Rural areas have none at all. By the time a patient gets seen, what was treatable becomes dangerous.

AI does not replace doctors. It buys time. And sometimes, time is everything.

---

## Dataset

HAM10k — 10,015 real dermoscopy images collected across 20 years from two continents. Seven types of skin lesions. Each image labeled by expert dermatologists.

| Class | Description |
|---|---|
| mel | Melanoma |
| nv | Melanocytic nevi |
| bcc | Basal cell carcinoma |
| akiec | Actinic keratoses |
| bkl | Benign keratosis |
| df | Dermatofibroma |
| vasc | Vascular lesions |

---

## Approach

ConvNextBase pretrained on ImageNet, fine-tuned on HAM10k. No tricks. No bloated pipelines. Just clean transfer learning on a problem that matters.

Augmentation: horizontal flip, rotation, color jitter, normalization.
Framework: PyTorch.
Training: Google Colab / local GPU.

---

## Results

| Metric | Score |
|---|---|
| Accuracy | 94% |
| F1 Score | 0.92 |
| Parameters | 88M |

---

## How to Run

```bash
git clone https://github.com/nudratabbas/skin-cancer-classification-convnext-ham10k
cd skin-cancer-classification-convnext-ham10k
pip install -r requirements.txt
jupyter notebook notebooks/main_analysis.ipynb
```

---

## About

Built by Nudrat Abbas, Healthcare Data Scientist and Kaggle Grandmaster.

If this helped you think differently about medical AI, consider giving it a star. It takes one second and means a lot.

<p align="center">
  <a href="https://www.linkedin.com/in/nudrat-abbas-664378324/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://www.kaggle.com/nudratabbas">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  </a>
  <a href="mailto:contact@nudratabbas.com">
    <img src="https://img.shields.io/badge/Email-C9A227?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://nudratabbas.com">
    <img src="https://img.shields.io/badge/Website-0C0C0C?style=for-the-badge&logo=google-chrome&logoColor=C9A227"/>
  </a>
</p>
