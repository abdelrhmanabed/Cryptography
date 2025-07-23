# 🔐 Image Encryption using Tiny Encryption Algorithm (TEA)

This project demonstrates how to encrypt and decrypt grayscale images using the **Tiny Encryption Algorithm (TEA)** in two modes of operation:

- **ECB (Electronic Codebook)**
- **CBC (Cipher Block Chaining)**

It allows the user to input their own encryption key and initialization vector (IV), and encrypt or decrypt BMP images via command-line interaction.


---

## 🔧 How It Works

### 🔑 TEA Encryption

- **Block cipher** using 64-bit blocks and a 128-bit key
- **32 rounds** of operation using XOR, shifts, and additions
- Works well for lightweight applications like image data

### 🖼️ Image Handling

- Images are loaded using `Pillow` (Python Imaging Library)
- Converted to grayscale to simplify encryption
- Image bytes are padded to match TEA's block size (8 bytes)

### 🧩 Modes of Operation

| Mode | Description |
|------|-------------|
| **ECB** | Encrypts each block independently. Patterns may remain visible. |
| **CBC** | XORs each block with the previous ciphertext. Adds randomness and stronger security. |


