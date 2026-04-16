🔐 X.509 Certificate Analysis (Browser-Based)

"Project" (https://img.shields.io/badge/Mini%20Project-Cybersecurity-blue)
"Method" (https://img.shields.io/badge/Method-Manual%20Analysis-green)
"Status" (https://img.shields.io/badge/Status-Completed-brightgreen)

---

📌 Aim

To download and analyze the SSL/TLS certificate of a website and decode its X.509 fields such as Issuer, Validity Period, Public Key, and Certificate Path.

---

🎯 Objectives

- Identify the Issuer of the certificate
- Determine the Validity Period
- Extract Public Key details
- Understand the Certificate Chain (Path of Trust)

---

🛠️ Method Used

This project is done using browser-based certificate inspection (no coding required).

---

🔍 Procedure

1. Open a secure website (https://www.google.com)
2. Click the 🔒 lock icon in the address bar
3. Select “Certificate is valid” / Certificate Viewer
4. Observe and record:
   - Issuer details
   - Validity period
   - Public key information
5. Identify the certificate chain

---

📊 Observations

🔹 Website

"*.google.com"

---

🔹 Issuer Details

- Common Name (CN): WE2
- Organization (O): Google Trust Services

---

🔹 Validity Period

- Issued On: 23 March 2026
- Expires On: 15 June 2026

---

🔹 Public Key Details

- SHA-256 fingerprint available
- Public key extracted from certificate viewer

---

🔹 Certificate Path (Trust Chain)

*.google.com
   ↓
WE2 (Intermediate CA)
   ↓
Google Trust Services (Root CA)

👉 This chain ensures the authenticity and trust of the website.

---

📂 Project Structure

x509-certificate-analysis/
│
├── README.md
├── certificate_details.txt
├── screenshots/
│   ├── issuer.png
│   ├── validity.png
│   ├── publickey.png

---

📸 Screenshots

Screenshots of the certificate viewer are included to provide proof of analysis.

---

📚 Key Concepts

- 🔐 X.509 Certificate: Standard for digital certificates
- 🌐 SSL/TLS: Ensures secure communication over the internet
- 🏢 Certificate Authority (CA): Issues digital certificates
- 🔗 Certificate Chain: Trust hierarchy from root CA to website

---

✅ Result

The SSL certificate of the website was successfully analyzed.
The following details were identified:

- Issuer
- Validity Period
- Public Key
- Certificate Path

---

👨‍💻 Author

Your Name
Computer Science Engineering Student

---

⭐ Note

This project demonstrates practical understanding of network security and digital certificates without using any programming.
