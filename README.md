
# 🔐 Password Vault with AES Encryption

## 📌 Project Overview

The **Password Vault** is a secure Java application that allows users to store and manage their credentials safely. It uses **AES (Advanced Encryption Standard)** to encrypt passwords before saving them, ensuring that sensitive information remains protected.

The vault is accessible only through a **master password**, and it supports features like **password storage, retrieval, update, deletion, and password strength checking & generation**.

---

## ✨ Features

* 🔑 **Master Authentication** – Secure login with a master password.
* 🔒 **AES Encryption & Decryption** – Ensures safe storage of credentials.
* 📂 **File Handling** – Passwords stored in encrypted format within files.
* 📝 **Add, View, Update, Delete Passwords** – Manage credentials easily.
* 🛡 **Password Strength Checker** – Warns if a password is weak.
* 🔧 **Password Generator** – Creates strong random passwords.
* 🎨 **(Optional)** GUI using **Swing/JavaFX**.

---

## 🛠 Tech Stack

* **Language**: Java (JDK 8+)
* **Encryption**: Java Cryptography API (AES)
* **Data Storage**: File Handling (`.txt` / `.dat`) or JDBC (optional)
* **UI**: Console-based (default), Swing/JavaFX (optional)

---

## 📂 Project Structure

```
PasswordVault/
│── src/
│   ├── Main.java            # Entry point
│   ├── User.java            # Handles master authentication
│   ├── Vault.java           # Add, view, update, delete passwords
│   ├── EncryptionUtil.java  # AES encryption & decryption logic
│── passwords.dat            # Encrypted credentials file
│── README.md                # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/password-vault.git
   cd password-vault
   ```
2. Compile the project:

   ```bash
   javac src/*.java
   ```
3. Run the program:

   ```bash
   java src/Main
   ```
4. Set a **master password** on first run.
5. Start storing and managing your credentials securely.

---

## 📸 Screenshots (Optional if you add GUI later)

* Console demo of adding and retrieving passwords.
* GUI window (if JavaFX/Swing implemented).

---

## 📈 Future Enhancements

* Integration with **MySQL database** using JDBC.
* Cross-platform desktop app with **JavaFX UI**.
* Cloud backup with **AES-256 encryption**.
* Export/import encrypted password files.

---

## 🧑‍💻 Author

Developed by **\[Your Name]**

* 💼 [LinkedIn](https://linkedin.com/in/dillibyaswanth/)
* 📂 [GitHub](https://github.com/your-dilli-yaswanth21/)
