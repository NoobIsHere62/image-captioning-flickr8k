# 🖼️ Image Captioning with Vision Transformer & Transformer Decoder

## 📖 Introduction
This project implements an end-to-end Image Captioning system using modern deep learning architectures. 
Instead of traditional CNN + LSTM, this model leverages:

- Vision Transformer (ViT) for image feature extraction
- Transformer Decoder for caption generation

The model is trained and evaluated on the Flickr8k dataset.

---

## 🚀 Features
- Extract image features using pretrained Vision Transformer (ViT)
- Generate captions using custom Transformer Decoder
- Beam Search for better caption generation
- BLEU score evaluation
- Gradio demo for real-time captioning
- Text-to-Speech (TTS) for accessibility support

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- PyTorch (for ViT)
- HuggingFace Transformers
- Gradio
- Google Colab

---

## 📊 Dataset
- Flickr8k Dataset
- ~8,000 images with 5 captions per image

---

## 🧠 Model Architecture

### 1. Image Encoder
- Pretrained Vision Transformer (ViT)
- Input: Image (224x224)
- Output: Feature vector

### 2. Caption Generator
- Custom Transformer Decoder
- Multi-head attention
- Positional encoding
- Sequence generation

---

## ⚙️ Training Pipeline
1. Load and preprocess images
2. Extract features using ViT
3. Clean and tokenize captions
4. Train Transformer Decoder
5. Evaluate using BLEU score

---

## 📈 Evaluation
- Metric: BLEU Score
- Beam Search used for better performance

---

## 🎯 Demo
- Upload image → Generate caption
- Convert caption to speech using gTTS

---

## ▶️ How to Run

1. Open notebook in Google Colab
2. Install dependencies: pip install transformers gradio gtts
3. Mount Google Drive
4. Run all cells

---

## 👤 Author
Nguyen Hoang Tuan

---

## 🔥 Future Improvements
- Replace ViT with CLIP
- Use full Transformer Encoder-Decoder
- Deploy as web app
