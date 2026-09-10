# 🛡️ DecodeLabs Cyber Security Industrial Training — Batch 2026

## 🔐 Cyber Security Projects 1–4

A collection of four practical cybersecurity projects developed as part of the **DecodeLabs Cyber Security Industrial Training Program – Batch 2026**.

The projects progress from basic security concepts to defensive security auditing:

> **Validate → Encrypt → Detect → Audit**

---

# 📚 Projects Overview

| Project | Title | Main Concept | Technology |
|---|---|---|---|
| 1 | 🔐 Password Strength Checker | Password Security | Python |
| 2 | 🔑 Basic Encryption & Decryption | Cryptography | Python |
| 3 | 🎣 Phishing Awareness Analysis | Threat Detection | Python |
| 4 | 🛡️ System Vulnerability Checklist | Security Auditing | Python + PowerShell |

---

# 🔐 Project 1 — Password Strength Checker

## 📌 Objective

Develop a Python-based password strength checker that evaluates whether a password follows basic security requirements.

## ✨ Features

- Password length validation
- Uppercase character detection
- Lowercase character detection
- Number detection
- Special-character detection
- Weak / Medium / Strong classification
- Input validation
- Security recommendations

## 🔍 Example

```text
Enter password: Hello123

Password Strength: MEDIUM

Recommendations:
- Add a special character
- Use a longer password

---

# 🔑 Project 2 — Basic Encryption & Decryption

## 📌 Objective

Develop a Python-based encryption and decryption program to understand the fundamentals of **cryptography**.

The project uses the **Caesar Cipher**, a classical substitution cipher in which each alphabetic character is shifted by a fixed number of positions.

## ✨ Features

- Text encryption
- Text decryption
- User-defined shift key
- Uppercase and lowercase character support
- Space preservation
- Special-character preservation
- Input validation
- Simple command-line interface
- Demonstration of encryption and decryption

## 🔄 Working Process

```text
Plaintext
    ↓
Select Shift Key
    ↓
Caesar Cipher
    ↓
Encrypted Ciphertext


---

# 🎣 Project 3 — Phishing Awareness Analysis

## 📌 Objective

The objective of Project 3 is to understand how phishing attacks exploit human behaviour and to develop a practical approach for identifying suspicious emails and messages.

The project focuses on recognizing common phishing indicators, analyzing suspicious links and messages, understanding social engineering techniques, and following a safe response process.

---

## 🎯 Key Goals

- Identify common phishing indicators
- Analyze suspicious emails and messages
- Detect suspicious URLs and domains
- Recognize social engineering techniques
- Understand attacker psychology
- Identify credential and financial requests
- Classify suspicious messages based on risk
- Develop cybersecurity awareness
- Follow a safe incident-response process

---

## ✨ Features

- 🎣 Phishing message analysis
- 🔗 Suspicious URL detection
- 📧 Sender and domain analysis
- ⚠️ Urgency and pressure detection
- 🔐 Credential-request detection
- 💰 Financial-request detection
- 📎 Suspicious attachment detection
- 🧠 Social engineering analysis
- 📊 Risk classification
- 🛡️ Security recommendations
- 🚨 Phishing red-flag checklist

---

# 🚩 Common Phishing Red Flags

The project focuses on identifying warning signs commonly found in phishing attempts.

### 1. 🚨 Urgency

Attackers may create a false sense of urgency.

```text
"Your account will be closed today."

"Immediate action required!"

"Your payment will be cancelled within 24 hours."

---

# 🛡️ Project 4 — System Vulnerability Checklist

## 📌 Objective

The objective of Project 4 is to develop a **System Vulnerability Checklist** that performs a basic security audit of a Windows system.

The application checks for common security weaknesses such as weak password policies, unsafe account configurations, firewall status, Windows Update status, screen-lock settings, and unsafe user practices.

The project follows a **Blue Team / Defensive Security** approach.

---

# 🎯 Key Goals

- Establish a basic system security baseline
- Identify common security weaknesses
- Check password and account security
- Check Windows Firewall configuration
- Review administrator accounts
- Check Windows Update status
- Review screen-lock configuration
- Identify unsafe user practices
- Assess security risks
- Provide security recommendations
- Generate an audit report

---

# ✨ Features

- 🖥️ System information collection
- 🔐 Password policy checking
- 👤 Guest account checking
- 🛡️ Windows Firewall checking
- 👨‍💻 Administrator account review
- 🔄 Windows Update service checking
- 🔒 Screen-lock checking
- ⚠️ User-practice checklist
- 📊 Risk-score calculation
- 🚦 Risk-level classification
- 💡 Security recommendations
- 📄 Security audit report generation
- 🖥️ Graphical User Interface

---

# 🏗️ System Architecture

```text
                    SYSTEM VULNERABILITY
                         CHECKLIST
                              │
                              ↓
                     Security Scanner
                              │
             ┌────────────────┼────────────────┐
             ↓                ↓                ↓
       Account Check     System Check     Security Check
             │                │                │
             ↓                ↓                ↓
       Password Policy   Windows Update    Firewall
       Guest Account     Screen Lock        User Practices
       Admin Accounts
             │                │                │
             └────────────────┼────────────────┘
                              ↓
                       Finding Analysis
                              ↓
                       Risk Assessment
                              ↓
                       Security Score
                              ↓
                     Recommendations
                              ↓
                       Audit Report
