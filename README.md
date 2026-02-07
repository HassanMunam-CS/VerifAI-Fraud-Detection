# VerifAI 🛡️ | Autonomous Fraud Defense System
> **Submission:** Gemini 3 Hackathon 2026  
> **Engine:** Google Gemini 3.0 (Pro & Flash Preview)

## 🚨 The Problem
Global digital fraud causes **$1 Trillion** in losses annually. In developing regions, users are targeted by:
* **Fake Banking Receipts:** Manipulated EasyPaisa/JazzCash screenshots.
* **Phishing Links:** SMS & WhatsApp messages designed to steal credentials.
* **Malware Artifacts:** Illegal software activators (like KMS) bundled with crypto-miners.

## 💡 The Solution
**VerifAI** is a client-side defense system that uses **Gemini 3.0 Computer Vision** to analyze screenshots and detect fraud in real-time. It identifies visual inconsistencies and malicious patterns that standard OCR might miss.

## 🚀 Key Features
* **One-Click Analysis:** Instant verification without account registration.
* **Model Hunter Logic:** An autonomous fallback loop that prioritizes **Gemini 3.0** for deep reasoning while maintaining 100% uptime by switching to Gemini 2.0 or 1.5 if regional quotas are hit.
* **Privacy-First:** Images are processed entirely in-memory within the browser.
* **Security-Conscious:** API keys are managed securely via a user-input interface to prevent quota theft and unauthorized usage.

## 🛠️ Tech Stack
* **AI Engine:** Google Gemini 3 API (`gemini-3-flash-preview`)
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (Zero Dependencies)
* **Logic:** Multimodal Image-to-Text Analysis

## 💻 Setup & Testing Instructions
1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/HassanMunam-CS/VerifAI-Fraud-Detection.git](https://github.com/HassanMunam-CS/VerifAI-Fraud-Detection.git)
