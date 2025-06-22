# 🔐 AES + LSB Image Steganography

This project securely hides text messages inside images using AES encryption and LSB steganography.

## 🚀 Features
- AES (EAX mode) encryption for confidentiality
- Least Significant Bit (LSB) image embedding
- Decryption and data extraction with integrity check
- Implemented in Python using Google Colab

## 📂 File Structure
- `steganography.ipynb`: Full implementation in Colab
- `main.py`: Python script version (optional)
- `cover_image.png`: Sample input image
- `stego_output.png`: Image with hidden message

## 📦 Requirements
```bash
pip install pillow pycryptodome
