# OCR Model using PyTorch

This is a custom-built **Optical Character Recognition (OCR)** system created using **PyTorch**. The model can extract and recognize text from images — ideal for scanned documents, screenshots, and more.

---

## 🔍 What is OCR?

**OCR (Optical Character Recognition)** is a technology that enables the detection and conversion of text from images into machine-encoded text. This can include printed text, handwritten text, or even text on natural scenes.

---

## 🧠 Model Overview

- ✅ Built from using **PyTorch- easyocr**
- 📸 Accepts images as input
- 🔡 Outputs recognized text
- 🧪 Pre-Trained model called easy ocr
- 🔧 Can be used for document scanning, image-based form reading, etc.

---

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **OpenCV** (for image processing)
- **NumPy**

---

## ⚙️ How it Works

1. Preprocess input image (grayscale, resize, normalize)
2. Pass image through a custom CNN/LSTM or transformer-based model
3. Decode output into readable text (e.g., using CTC loss or softmax decoding)

---

