🔐 X.509 Certificate Analysis 

---

📌 1. Introduction

Secure communication over the internet is achieved using SSL/TLS protocols and X.509 digital certificates.
These certificates ensure authentication, data integrity, and encryption between client and server.

This project demonstrates how to analyze a real-world SSL certificate and extract its important components.

---

🎯 2. Aim

To download and analyze the SSL/TLS certificate of a website and decode its X.509 fields such as:

- Issuer
- Validity Period
- Public Key
- Certificate Path

---

🧠 3. Objectives

- Identify certificate issuer
- Determine validity period
- Extract public key details
- Understand certificate trust chain

---

🛠️ 4. Tools Used

- Web Browser (Chrome / Mobile Browser)
- Internet Connection

---

🔍 5. Procedure

1. Open https://www.google.com
2. Click 🔒 lock icon
3. Open Certificate Viewer
4. Observe certificate details
5. Record:
   - Issuer
   - Validity Period
   - Public Key
6. Identify certificate chain

---

📊 6. Observations

🔹 Website

"*.google.com"

---

🔹 Issuer

- Common Name (CN): WE2
- Organization: Google Trust Services

---

🔹 Validity Period

- Issued On: 23 March 2026
- Expires On: 15 June 2026

---

🔹 Public Key

- SHA-256 fingerprint available
- Public key extracted from certificate

---

🔗 Certificate Path

*.google.com
   ↓
WE2 (Intermediate CA)
   ↓
Google Trust Services (Root CA)

---

📂 7. Project Structure

x509-certificate-analysis/
│
├── README.md
│   └── Complete project documentation
│
├── certificate_details.txt
│   └── Contains issuer, validity, public key details
│
├── certificate_path.txt
│   └── Contains certificate trust chain
│
├── project_report.docx
│   └── Full formatted project report (for submission)
│
├── screenshots/
│   ├── issuer.png
│   ├── validity.png
│   ├── publickey.png

---

📄 8. certificate_path.txt

Certificate Path:
1. *.google.com
2. WE2
3. Google Trust Services

---

📘 9. Project Report (docx)

A detailed project report has been created and included as:
📄 "project_report.docx"

It contains:

- Introduction
- Aim
- Procedure
- Observations
- Result
- Conclusion

---

📸 10. Screenshots

Screenshots are included in the project to show:

- Issuer details
- Validity period
- Public key information

---

📚 11. Key Concepts

- X.509 Certificate → Standard digital certificate format
- SSL/TLS → Secure communication protocol
- Certificate Authority (CA) → Trusted issuer
- Certificate Chain → Trust hierarchy

---

✅ 12. Result

The SSL certificate of the website was successfully analyzed.
The following details were identified:

- Issuer
- Validity Period
- Public Key
- Certificate Path

---

🚀 13. Conclusion

This project helped in understanding how websites maintain secure communication using digital certificates and trust chains.

---

👨‍💻 Author

Your Name
Computer Science Engineering Student

---

⭐ Final Note

This project demonstrates practical knowledge of network security concepts using real-world certificate analysis without coding.
