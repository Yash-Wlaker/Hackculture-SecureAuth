# SecureAuth AI
### AI-Powered Passwordless Authentication & Deepfake Protection for Financial Platforms

> A solution developed for the **SEBI Securities Market TechSprint 2026**
> Target: AI-Driven Detection of Synthetic Media and Phishing Attacks

---

## Overview

SecureAuth AI is a next-generation cybersecurity platform designed to protect investors from modern cyber threats including:

- 🎭 Deepfake videos & voice attacks
- 🎣 AI-generated phishing campaigns
- 🔑 Password theft
- 📱 OTP interception
- 🌐 Fake financial websites
- 📧 Spoofed emails and messages

Instead of relying on passwords or OTPs, SecureAuth AI uses **Passkeys (FIDO2)**, **AI-powered liveness detection**, and **cryptographic verification** to provide secure and seamless authentication.

---

# Problem Statement

Financial platforms are increasingly targeted using AI-generated attacks.

Current challenges include:

- Deepfake videos impersonating regulators
- Voice cloning attacks
- Fake brokerage websites
- Phishing emails pretending to be SEBI, NSE, BSE or brokers
- Password and OTP theft
- No reliable way for investors to verify official communications

SecureAuth AI addresses these challenges through a multi-layered security architecture.

---

# Features

## Passwordless Authentication

- FIDO2 Passkeys
- Hardware-backed authentication
- No passwords
- No SMS OTPs

---

## AI Liveness Detection

Detects:

- Printed photos
- Screen replays
- Video loop attacks
- Deepfake faces

Uses AI models to verify that the user is physically present during authentication.

---

## Browser Security Extension

The browser extension:

- Detects phishing websites
- Verifies SSL certificates
- Checks communication authenticity
- Displays trusted verification badges
- Warns users about spoofed pages

---

## Verified Financial Communications

SecureAuth AI validates communications from:

- SEBI
- NSE
- BSE
- Registered brokers
- Financial institutions

Only digitally signed messages receive a verified badge.

---

## Cross Device Protection

If login occurs from an unknown device:

- Primary device receives notification
- User identity verification is required
- Unauthorized access is blocked

---

# Architecture

```
                    +----------------------+
                    |   Investor Device    |
                    +----------+-----------+
                               |
                     Passkey Authentication
                               |
               +---------------+----------------+
               |                                |
        AI Liveness Engine             Browser Extension
               |                                |
        Face Verification          Website Verification
               |                                |
               +---------------+----------------+
                               |
                  SecureAuth Verification
                               |
             Verified Financial Platform
```

---

# Technology Stack

## AI

- CNN-based Liveness Detection
- Deepfake Detection
- Face Authentication

## Authentication

- FIDO2
- Passkeys
- Secure Enclave
- Public Key Cryptography

## Browser

- Browser Extension
- DOM Inspection
- SSL Verification
- Certificate Validation

## Security

- Public/Private Key Infrastructure
- Digital Signatures
- Cryptographic Verification

---

# Security Workflow

1. User opens financial platform.
2. Browser extension verifies authenticity.
3. User signs in using Passkey.
4. AI performs facial liveness detection.
5. Cryptographic verification confirms identity.
6. Access granted only after successful verification.

---

# Benefits

- No passwords
- No OTP fraud
- Strong phishing protection
- Deepfake resistance
- Verified communications
- Faster authentication
- Improved investor trust

---

# Challenges Addressed

## Operating System Restrictions

SecureAuth AI respects operating system privacy protections by requesting visible user authorization before camera access.

## Browser Sandbox

The browser extension focuses on web-based financial portals and validates communications without requiring kernel-level access.

---

# Future Roadmap

- Voice Deepfake Detection
- Blockchain-based Digital Identity
- Decentralized Certificate Verification
- Post-Quantum Cryptography
- Advanced Behavioral Biometrics
- AI Risk Scoring Engine

---

# Project Team

| Member | Role |
|---------|------|
| Nitesh Mali | Team Leader & Core Architect |
| Yash Lakhatariya | Security & Systems Engineer |
| Krunal Chavda | AI Models & Liveness Optimization |
| Rudra Parmar | Browser Extension & Frontend Integrations |

---

# Repository Structure

```
SecureAuth-AI/
│
├── README.md
├── docs/
├── backend/
├── frontend/
├── browser-extension/
├── mobile-sdk/
├── ai-models/
├── api/
├── assets/
├── diagrams/
└── LICENSE
```

---

# Vision

SecureAuth AI aims to build a passwordless, phishing-resistant, and AI-secure financial ecosystem where every transaction and communication can be trusted.

---

## Built For

**SEBI Securities Market TechSprint 2026**

Target:
**AI Driven Detection of Synthetic Media and Phishing Attacks**

---

## License

This project is developed for research, innovation, and the SEBI TechSprint challenge.
