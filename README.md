# secure_data_encryption
Secure-Data-Encryption-System-Using-Streamlit
🔐 Secure Data Encryption System
An Academic Project for Secure Data Handling with Python & Streamlit
________________________________________
📘 Overview
A Streamlit-powered web application designed to encrypt and securely store sensitive data using user-defined passkeys. The app leverages AES-level encryption (via cryptography. Fernet) and ensures robust security with intelligent access control mechanisms.
________________________________________
🧠 Key Features
• 🔐 Secure Encryption: Safely encrypt and store any text input using a passkey.
• 🔍 Easy Retrieval: Retrieve your data using a unique UUID and the same passkey.
• 🔒 Access Control: System locks after 3 failed attempts—requires master password to reauthorize.
• 🔁 Smooth UX: Sidebar-driven navigation and seamless page transitions.
• 🛡️ AES-Level Security: Powered by Python’s cryptography and hashlib libraries.
________________________________________
⚙️ Tech Stack
• Python 3.13
• Streamlit
• Cryptography (Fernet)
• Hashlib, UUID, Base64
________________________________________
🚀 Getting Started
Install Dependencies pip install -r requirements.txt pip install streamlit cryptography 4. Launch the App streamlit run secure_data_app.py
________________________________________
📁 Project Structure
secure-data-encryption/
├── 🔸 secure_data_app.py # 🚀 Main Streamlit application
├── 📦 requirements.txt # 📋 Python dependency list
└── 📘 README.md # 📝 Project overview and documentation
🧾 Description
• secure_data_app.py – Core application logic built with Streamlit.
• requirements.txt – All required Python packages for smooth installation.
• README.md – Everything I need to understand, run, and contribute to the project.
🔐 How It Works
• Encrypt & Store:
o Input text + create a passkey
o Confirm passkey → receive a unique UUID
• Retrieve Data:
o Enter the UUID + same passkey
o Your original message is decrypted and returned
• Security Lock:
o 3 wrong attempts trigger a lock
o Reauthorization required via the Login page
o Default master password: Govpia@1234
________________________________________
🙌 Acknowledgements
Inspired by best practices in secure app development using Python & Streamlit. Created as part of an academic learning journey.
________________________________________
📜 License
For educational and demonstration purposes only.
________________________________________
🚀 Deployment Setup for Streamlit Cloud
To deploy on Streamlit Cloud, you need:
🧾 Files Required:
• secure_data_app.py (your main app)
• requirements.txt
🌐 Steps:
1.	Push your project to GitHub.
2.	Go to streamlit.io/cloud and connect your GitHub repo.
3.	Select the branch and entry point (e.g. secure_data_app.py).
4.	Click Deploy.

