# 🎥 Human Action Recognition with I3D — End-to-End Pipeline

This repository presents a **complete end-to-end pipeline for human action recognition in videos** using the **I3D (Inflated 3D ConvNet)** model pre-trained on the **Kinetics-400** dataset, directly from **TensorFlow Hub**.

The project covers everything from **video download and preprocessing** to **model inference and interpretation of predictions**, following clean code and reproducible practices.

---

## 📘 Available Guides

🔹 [Guia Passo a Passo — Reconhecimento de Ações com I3D (Português)](./Guia_Passo_a_Passo_(Português).ipynb)  
🔹 [Step-by-Step Guide — Action Recognition with I3D (English)](./Guide_Step_by_Step_(English).ipynb)

Each guide explains in detail how to:
- Download sample videos from public datasets (UCF101).
- Load and manage action labels from **Kinetics-400**.
- Preprocess videos using **OpenCV** (frame extraction, resizing, normalization).
- Load the **I3D model** from **TensorFlow Hub**.
- Prepare video tensors in the expected input format.
- Run inference and extract action probabilities.
- Interpret results, including **top-1** and **top-5** predicted actions.

---

## 🚀 Notebooks

👉 **Action_Recognition (Clean Code).ipynb**  
Clean and well-structured notebook containing the full implementation of the action recognition pipeline, suitable for study, reuse, and extension.

👉 **Guia_Passo_a_Passo_(Português).ipynb**  
Detailed explanation in Portuguese, focused on learning and conceptual understanding.

👉 **Guide_Step_by_Step_(English).ipynb**  
English version of the step-by-step guide, suitable for international audiences.

---

## 🧠 Model Overview

- **Architecture:** I3D (Inflated 3D Convolutional Network)
- **Dataset:** Kinetics-400 (400 human action classes)
- **Input:** Video clips as sequences of RGB frames
- **Output:** Probability distribution over action classes

The I3D model captures **spatio-temporal features**, making it particularly effective for video-based action recognition tasks.

---

## 📚 References

- **TensorFlow Hub Tutorial — Action Recognition with I3D:**  
  https://www.tensorflow.org/hub/tutorials/action_recognition_with_tf_hub?hl=pt-br

- **TensorFlow Hub — Video Classification Models:**  
  https://tfhub.dev/s?module-type=video-classification

- **Udemy Course — TensorFlow Hub: Deep Learning, Computer Vision and NLP**  
  (Course-based inspiration and learning reference)

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share.
