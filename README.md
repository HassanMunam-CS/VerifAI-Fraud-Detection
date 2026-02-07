# VerifAI 🛡️ | Autonomous Fraud Defense System

> **Winner:** Google Gemini AI Hackathon 2025 (Submission)
> **Powered by:** Google Gemini 2.0 Flash Lite

## 🚨 The Problem
Global digital fraud causes **$1 Trillion** in losses annually.
In developing regions (like Pakistan), elderly and non-technical users are targeted daily by:
* Fake Banking Receipts (EasyPaisa/JazzCash)
* Phishing SMS & WhatsApp Links
* "Account Suspended" Scams

## 💡 The Solution
**VerifAI** is a client-side, autonomous defense system that instantly analyzes screenshots to detect fraud.
It uses **Computer Vision + LLM Reasoning** to spot inconsistencies that humans miss.

## 🚀 Key Features
* **One-Click Analysis:** No login required. Just upload and check.
* **Privacy-First:** Serverless architecture. Images are processed in memory and never stored.
* **Cross-Platform:** Works on Desktop, Mobile (Android/iOS), and Tablets.
* **Resilient Engine:** Uses a custom **"Model Hunter"** algorithm to switch between `Gemini 2.0 Flash` and `Flash Lite` to bypass quota limits.

## 🛠️ Tech Stack
* **AI Engine:** Google Gemini API (`gemini-2.0-flash-lite-preview`)
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (Zero Dependencies)
* **Deployment:** GitHub Pages / Vercel (Ready)

## 📸 How It Works
1.  **User uploads** a screenshot (e.g., a suspicious SMS).
2.  **VerifAI sends** the image to Gemini 2.0 Flash Lite.
3.  **The AI analyzes** text patterns, URL structures, and visual artifacts.
4.  **Result:** "VERIFIED SAFE" ✅ or "FRAUD DETECTED" 🚨 with a clear explanation.

## 💻 Setup & Usage
1.  Clone the repo:
    ```bash
    git clone [https://github.com/HassanMunam-CS/VerifAI-Fraud-Detection.git](https://github.com/HassanMunam-CS/VerifAI-Fraud-Detection.git)
    ```
2.  Open `index.html` in any browser.
3.  (Optional) Add your own API Key in the code if the quota runs out.

## 🛡️ License
MIT License. Open Source for the Community.
