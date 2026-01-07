# Password Cracking Demo

An interactive educational tool demonstrating common password attack techniques through browser-based demonstrations. This project is designed for GCSE Computer Science and KS3 Digital Technology students to understand the importance of strong passwords and secure authentication practices.

## 📋 Overview

This project contains interactive, browser-based demonstrations of two fundamental password cracking attack methods:

- **Brute Force Attack**: Systematically tries every possible combination of characters until the correct password is found
- **Dictionary Attack**: Uses a pre-compiled wordlist of common passwords and words to attempt password cracking more efficiently

All demonstrations run entirely in the browser with no server-side processing required, making it perfect for educational environments.

## 🎯 Purpose

The primary goal of this project is to provide students with a hands-on understanding of:

- How password vulnerabilities can be exploited
- The importance of password length and complexity
- The computational resources required to crack passwords
- Different password attack methodologies
- Why proper password security practices matter

## 🚀 Features

### Brute Force Demonstrator
- Interactive password input interface
- Real-time attempt counter and timer
- Displays current guess attempts
- For passwords up to 6 characters: performs actual brute force cracking
- For longer passwords: calculates and displays estimated crack time
- Alphanumeric character support (A-Z, a-z, 0-9)

### Dictionary Attack Demonstrator
- Pre-loaded rockyou wordlist (gzip-compressed)
- Client-side decompression and loading
- Real-time dictionary loading status
- Tracks attempts and elapsed time
- Live profanity filter for display
- Attempts passwords from a real-world compromised password database

## 📁 Project Structure

```
PasswordCrackingDemo/
├── index.html                 # Main landing page with demo links
├── brute-force.html          # Brute force attack demonstrator
├── dictionary-attack.html    # Dictionary attack demonstrator
├── wordlists/
│   └── rockyou.txt.gz       # Compressed common passwords wordlist
├── LICENSE                   # GNU Affero General Public License v3
└── README.md                # This file
```

## 🛠️ Technology Stack

- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Responsive utility-first styling
- **Vanilla JavaScript**: Core attack algorithm implementations
- **Pako**: Browser-based gzip decompression library
- **JetBrains Mono**: Monospace font for authentic code aesthetic

## 📊 Educational Content

The demonstrations are designed to teach:

1. **Algorithm understanding**: How attack methods iterate through password possibilities
2. **Performance analysis**: Time complexity and computational requirements
3. **Security awareness**: Why weak passwords are vulnerable
4. **Practical cryptography**: Real-world attack techniques used in cybersecurity

## ⚠️ Important Notes

- **Educational Use Only**: These demonstrations are for learning purposes only
- **Ethical Use**: Students should understand and respect privacy and security laws
- **Browser-Based**: All processing happens locally in the browser - no data is sent to servers
- **Safe Learning Environment**: Designed to be used in classroom or supervised settings

## 📖 How to Use

1. Open `index.html` in a web browser
2. Select either the **Brute Force Attack** or **Dictionary Attack** demonstrator
3. Follow the on-screen instructions
4. Observe how the attack method attempts to crack the password
5. Analyze the results to understand the attack's efficiency

## 🔗 Hosting

This project is hosted as a GitHub Pages static site, making it freely accessible online for educational institutions.

## 📜 License

Licensed under the GNU Affero General Public License v3 (AGPL-3.0)

See [LICENSE](LICENSE) for details.

## 👨‍🏫 Educational Context

- **Curriculum**: Curriculum for Wales Support
- **Level**: GCSE Computer Science / KS3 Digital Technology
- **Author**: Bassaleg School
- **Repository**: [GitHub - PasswordCrackingDemo](https://github.com/Bassaleg-School/PasswordCrackingDemo)

---

**Disclaimer**: This project is created for educational purposes to help students understand cybersecurity concepts and the importance of password security. Users are responsible for using this tool ethically and in accordance with all applicable laws and regulations.
