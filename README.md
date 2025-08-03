# 🖼️ Image Encryption & Decryption Tool 🔐

A simple Python project to encrypt and decrypt images using **pixel manipulation techniques**. This tool applies basic mathematical operations on pixel values to scramble and unscramble an image.

---

## 💡 Features

- Encrypt images by manipulating pixel RGB values
- Decrypt back to the original image using the same key
- Lightweight and beginner-friendly
- Easily extendable to more complex logic or GUI

---

## 📷 How It Works

- Each pixel's Red, Green, and Blue (RGB) values are modified using a secret key.
- For encryption, values are increased using `(value + key) % 256`.
- For decryption, the same key is subtracted to reverse the changes.

---

## 🛠️ Requirements

- Python 3.x
- Pillow library

Install dependencies:
```bash
pip install pillow


⚠️ Disclaimer
This project is educational and does not use cryptographically secure methods. Do not use it for real-world sensitive image encryption.


Note:📄 Internship Task Description
Internship Task 2 – Image Encryption Tool (Prodigy InfoTech)

As part of my second internship task at Prodigy InfoTech, I developed a basic image encryption tool using pixel-level manipulation. The tool applies simple mathematical operations to each pixel of an image, allowing users to encrypt and decrypt images using a user-defined encryption key.

The encryption process involves modifying the RGB values of each pixel based on the provided key. While the encryption works effectively, the simplicity of the technique results in a limitation: the decrypted image does not perfectly match the original and may exhibit a slight loss in quality. This is due to the basic arithmetic operations used, which are not lossless or cryptographically secure.

This task helped me understand fundamental concepts of image processing, pixel manipulation, and the importance of using secure algorithms in encryption and decryption processes.
