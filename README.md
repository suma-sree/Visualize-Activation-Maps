# Emotion Detection — CNN Activation Map Visualization

This project demonstrates how to visualize **activation maps** from a **pretrained CNN (Mini-Xception)** used for **facial emotion detection**. The goal is to understand which regions of an input image activate different filters in the convolutional layers.

---

## 📌 Description

We use a **pretrained Mini-Xception model** trained on the **FER2013 dataset** to classify facial emotions such as:

- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

By passing a test face image through the model and extracting feature maps from convolutional layers, we can visualize **which parts of the image activate different CNN filters**.

---

## 🚀 How to Run

1. Clone this repository or download the script.
2. Install required packages:

```bash
pip install -r requirements.txt
