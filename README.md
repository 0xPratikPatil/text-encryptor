# 🔐 PHP Text Encrypter

## 🚀 Overview

PHP Text Encrypter is a **simple encryption and decryption tool** built in **PHP**. It allows users to securely encrypt and decrypt text or files using a user-provided key. The system uses a session-based approach to process encryption and decryption results.

## ✨ Features

-   🔒 **Encrypt Text or Files** – Securely encrypt text or uploaded files.
    
-   🔑 **Key-Based Security** – Requires a strong encryption key (8+ characters).
    
-   🔓 **Decrypt with Key** – Restore original content using the same encryption key.
    
-   📂 **File Support** – Encrypt and decrypt text-based files.
    
## 📸 Demo
<img width="805" alt="Screenshot 2025-03-31 at 3 09 20 PM" src="https://github.com/user-attachments/assets/dee4bc66-b44f-4946-9d4b-cf95eb80b158" />

<img width="805" alt="Screenshot 2025-03-31 at 3 09 56 PM" src="https://github.com/user-attachments/assets/2d4cbc1d-3a97-45a7-bf60-8b8329ed14c3" />


## 🛠 Installation

### Prerequisites

-   PHP installed
-   `fake_hash.php` file for encryption logic
    

### Steps

1.  Clone the repository
```sh
git clone https://github.com/0xPratikPatil/text-encryptor.git
cd text-encrypter
```
2.  Start a local PHP server

```sh
php -S localhost:8000
```

3.  Open `http://localhost:8000` in your browser.
    
4.  Enter text or upload a file, provide a key, and encrypt or decrypt the data.
    

## 📌 Usage

### **Encrypt Text/File**

-   Enter text or upload a file.
    
-   Provide an **encryption key** (must be 8+ characters).
    
-   Click **Encrypt**, and the encrypted output will be shown.
    

### **Decrypt Text/File**

-   Upload an encrypted file or paste encrypted text.
    
-   Provide the same **key used for encryption**.
    
-   Click **Decrypt**, and the original text will be restored.
    

## 🏗 Tech Stack

-   **Backend:** PHP
    
-   **Encryption Logic:** `fake_hash.php` (custom encryption logic)

## 📌 Roadmap

-   **Basic text encryption and decryption**
    
-   **File encryption support**
    
-   **AES encryption instead of custom hashing**
    
-   **Hash verification for file integrity**
    
-   **User authentication for secure encryption storage**
    
-   **Support for multiple encryption algorithms**
    
-   **Web-based UI improvements**
    

## 🤝 Contributing

Contributions are welcome! To contribute:

1.  Fork the repository.
    
2.  Create a new branch (`feature-name`).
    
3.  Commit your changes.
    
4.  Open a pull request.
    

## 🛡 License

This project is licensed under the **MIT License**.

Made with ❤️ by the **PHP Text Encrypter Team** 🔐
