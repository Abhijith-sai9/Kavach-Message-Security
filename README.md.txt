
# 🛡️ Project Kavach - Secure Message System

## 📌 Overview
Project Kavach is a secure web-based application that hides secret messages inside images using **AES encryption and Steganography**. It demonstrates how data security and encryption techniques can be used to protect sensitive information.

---

## 🚀 Features
- AES Encryption of secret messages
- Hide encrypted data inside images (Steganography)
- Decrypt hidden messages using password
- Simple web interface using Flask
- Secure and lightweight system

---

## 🧠 Technologies Used
- Python
- Flask
- HTML, CSS
- Pillow (PIL)
- Cryptography (AES Encryption)

---

## ⚙️ How It Works
1. User uploads an image  
2. Enters secret message and password  
3. Message is encrypted using AES  
4. Encrypted data is hidden inside image pixels  
5. User downloads encrypted image  
6. Same image + password is used to retrieve message  

---

## 🛠️ Installation

Install required libraries:
```bash
pip install flask pillow cryptography