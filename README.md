# 🔐 AES + LSB Image Steganography

This project securely hides text messages inside images using AES encryption and LSB steganography.

## 🚀 Features
- AES (EAX mode) encryption for confidentiality
- Least Significant Bit (LSB) image embedding
- Decryption and data extraction with integrity check
- Implemented in Python using Google Colab

## 📂 File Structure
- `AES_steganography.ipynb`: Full implementation in Colab
- `cover_image.png`: Sample input image
- `stego_output.png`: Image with hidden message

---

## 📦 Libraries Required

| Library        | Purpose                                   |
|----------------|-------------------------------------------|
| `Pillow`        | Image processing and pixel manipulation   |
| `pycryptodome`  | AES encryption/decryption (EAX mode)      |

Install using:

```bash
pip install pillow pycryptodome
