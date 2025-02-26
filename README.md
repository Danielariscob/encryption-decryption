# Encryption and Decryption

#### 📌 Project Overview

This project implements a Columnar Transposition Cipher for encrypting and decrypting messages in Python. 
The transposition cipher is a simple yet effective way of encrypting a text by rearranging its characters.

#### 📂 Project Structure
 
 - 📄 Encryption_Decryption.ipynb
 - 📄 README.md

#### 🔧 Features

- A **TranspositionCipher** class that includes:
  - `__init__(self, key)`: Initializes the cipher with a key.
  - `encrypt(self, message)`: Encrypts a given plaintext message.
  - `decrypt(self, ciphertext)`: Decrypts an encrypted message.
- A function to **hack the cipher** without knowing the key (optional).

#### 🛠️ Usage

1. Create an instance of `TranspositionCipher` with a key:
   ```python
   cipher = TranspositionCipher(5)
   ```
2. Encrypt a message:
   ```python
   encrypted = cipher.encrypt("Hello, this is a secret message!")
   ```
3. Decrypt the message:
   ```python
   decrypted = cipher.decrypt(encrypted)
   ```

#### 🎯 Optional Challenge

- The `hack_cipher` function attempts to decrypt a ciphertext by trying different key lengths.

#### ➡️ How to Run

- Open the Jupyter Notebook (`Encryption_Decryption.ipynb`) and execute the cells.

#### 📬 Contact

For questions or collaboration, reach out via LinkedIn or check my portfolio at daniela-risco.com.
