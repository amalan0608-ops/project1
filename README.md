# project1

SecureKit — Cyber Security Tools

SecureKit is a browser-based Cyber Security Tools Directory designed for students, developers, cybersecurity learners, and security professionals.

It provides a collection of cybersecurity tools organized into categories such as Network, Defense, Web Security, Forensics, Cryptography, Malware Analysis, Cloud Security, and Identity.

The project also includes two small browser-based utilities:

- Password Strength Checker
- SHA-256 Hash Generator

«Educational Purpose: Use scanning and testing tools only on systems you own or have explicit permission to test.»

---

🚀 Features

🔐 Password Strength Checker

The built-in password analyzer estimates password strength based on:

- Password length
- Lowercase characters
- Uppercase characters
- Numbers
- Special characters
- Common password patterns
- Repeated characters

It provides four levels:

- Weak
- Fair
- Good
- Strong

The password is processed locally in the browser.

---

🔑 SHA-256 Hash Generator

The SHA-256 utility converts entered text into a SHA-256 cryptographic hash.

It uses the browser's Web Crypto API:

crypto.subtle.digest("SHA-256", ...)

This can be useful for learning about:

- Cryptographic hashing
- File/text integrity
- Checksum comparison
- Digital security concepts

---

🛡️ Cybersecurity Tool Directory

SecureKit contains 39 cybersecurity tools.

🌐 Network Security

- Nmap
- Wireshark
- Zeek
- Suricata
- pfSense
- WireGuard

🛡️ Defense & Monitoring

- Snort
- OSSEC / Wazuh
- Bitwarden
- Security Onion
- Lynis
- Fail2Ban
- ClamAV

🌍 Web Security

- OWASP ZAP
- Burp Suite
- Nikto
- OpenVAS
- Wapiti
- ModSecurity
- Mozilla Observatory

🔎 Digital Forensics

- Autopsy
- Volatility
- The Sleuth Kit
- FTK Imager

🔐 Cryptography

- VeraCrypt
- GnuPG
- Cryptomator
- Let's Encrypt

🦠 Malware Analysis

- Ghidra
- YARA
- Cuckoo / CAPE

☁️ Cloud Security

- Trivy
- Prowler
- Gitleaks

👤 Identity & Authentication

- Keycloak
- KeePassXC
- YubiKey
- Have I Been Pwned

---

🎯 Tool Categories

The website includes interactive category filtering.

Users can select:

All
Network
Defense
Web
Forensics
Crypto
Malware
Cloud
Identity

The JavaScript dynamically updates the displayed tools without reloading the page.

---

💻 Technologies Used

Frontend

- HTML5
- CSS3
- JavaScript
- Web Crypto API
- CSS Grid
- Responsive Design

External Resource

The project uses the Schibsted Grotesk font through Google Fonts.

---

📁 Project Structure

The project can be kept as a simple single-file website:

SecureKit/
│
├── index.html
└── README.md

"index.html"

Contains:

- HTML structure
- CSS styling
- Cybersecurity tools database
- Category filtering
- Password strength calculator
- SHA-256 hashing functionality
- Responsive layout
- Accessibility features

"README.md"

Project documentation and usage instructions.

---

▶️ How to Run

Method 1 — Browser

Simply open:

index.html

in a modern web browser.

Method 2 — Local Server

You can also run it using a local development server.

For example:

python -m http.server 8000

Then open:

http://localhost:8000

---

🔒 Security & Privacy

The password-strength checker and SHA-256 text hashing utilities operate inside the browser.

The website does not require a backend server or database for these utilities.

The project also provides an important security warning:

«Use scanning and testing tools only on systems you own or have written permission to test.»

Always follow applicable laws, organizational policies, and responsible security-testing practices.

---

♿ Accessibility

The interface includes several accessibility-oriented features:

- Semantic HTML
- Keyboard focus indicators
- ARIA labels
- "aria-live" output for dynamic results
- Reduced-motion support
- Responsive layout
- High-contrast interface elements

---

📱 Responsive Design

The interface is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile devices

CSS Grid automatically adjusts the tool cards based on available screen width.

---

🎨 User Interface

The website provides:

- Clean cybersecurity-focused design
- Light and dark theme support
- Responsive navigation
- Interactive category filters
- Tool cards
- Security utilities
- Educational security recommendations

The interface automatically supports the user's system color preference and also defines explicit light/dark theme variables.

---

🧠 Security Best Practices

SecureKit recommends five basic security habits:

1. Use a password manager and a unique password for every account.
2. Enable multi-factor authentication, preferably using a passkey or security key.
3. Install operating-system, browser, and application updates promptly.
4. Maintain offline or versioned backups and regularly test restoration.
5. Check links and attachments before opening them, even when they appear to come from known senders.

---

⚠️ Disclaimer

SecureKit is an educational cybersecurity directory.

The website provides descriptions and links to external cybersecurity tools. Tool functionality, licensing, availability, and features may change over time.

Always check the official website of each project for the latest information.

Do not use cybersecurity tools against systems, networks, websites, accounts, or data without authorization.

---

👨‍💻 Project Type

Project: Cyber Security Tools Directory

Application Type: Educational Web Application

Platform: Web Browser

Frontend: HTML5 + CSS3 + JavaScript

Architecture: Client-side / Static Website

---

📜 License

This project can be used for educational and academic purposes.

The external cybersecurity tools listed in the directory are separate projects and remain subject to their respective licenses and terms of use.

---

⭐ Future Improvements

Possible future versions could include:

- Search functionality
- Tool bookmarking
- Tool comparison
- Tool ratings
- Cybersecurity news section
- Learning resources
- Security quiz module
- Interactive security labs
- Vulnerability learning simulations
- Security checklist
- Exportable security reports
- PWA/mobile installation support
- More browser-based security utilities

---

📌 Credits

Created as an educational cybersecurity project for learning about cybersecurity tools, defensive security, cryptography, network security, web security, and digital forensics.
