# Quantum-Enhanced Secure Email API

A secure email system implementing **quantum-resistant cryptographic algorithms** for enhanced security in the post-quantum era.

---

## 🔐 Overview

This project provides an API and a minimal **HTML frontend** for secure email communication using **quantum-safe encryption standards**. It includes:

- User authentication (with optional Zero-Knowledge Proofs)
- End-to-end encrypted email exchange
- Wallet-based cryptographic key management

---

## 🧠 Features

- **Quantum-Resistant Cryptography**
  - Hybrid RSA-4096 + AES-256
  - Extended RSA-8192
  - Hash-Based Signatures
  - AES-256-GCM (Extended Key Support)
  - Zero-Knowledge Schnorr Proofs

- **Secure Email Exchange**
  - End-to-end encrypted emails
  - Plain-to-encrypted email support

- **Wallet & Key Management**
  - Store and manage cryptographic keys securely

- **Frontend**
  - Minimal HTML interface for demo/testing

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- FastAPI
- Cryptography Libraries

### Installation

```bash
git clone https://github.com/karthekeya190/Quantum-secure-email-client.git
cd quantum-enhanced-secure-email
pip install fastapi uvicorn pydantic cryptography
Running the Server
bash
python main.py
Visit: http://localhost:8000
HTML frontend available at / (root path)
