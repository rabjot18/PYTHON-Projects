# 🔐 Simple Python Password Manager

This is a beginner-friendly Python project that allows you to securely store and retrieve passwords using symmetric encryption from the `cryptography` package. It runs entirely in the terminal and is a great way to practice file handling, encryption, and basic Python logic.

---

## 💡 Features

- Add a new password securely
- View stored passwords after decrypting them
- Uses `Fernet` encryption from the `cryptography` library
- Stores data in a local `passwords.txt` file
- Encryption key is stored separately in a `key.key` file
- Simple terminal-based interaction

---

## 🛠 Requirements

- Python 3.6 or higher
- [`cryptography`](https://pypi.org/project/cryptography/) library

### Install `cryptography` (if not already installed):

```bash
pip3 install --break-system-packages cryptography
