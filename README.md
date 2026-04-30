## ReturnGuard.ai | Neural Fraud Mitigation Suite
Developed by: Vishnu Rathan B

Institution: Saveetha Engineering College

Department: B.Tech Artificial Intelligence and Machine Learning

## 📌 Project Overview
ReturnGuard.ai is a multi-node security simulation designed to identify and suppress sophisticated e-commerce fraud patterns. The project demonstrates a decentralized architecture where individual user nodes (Marketplace, Madhan, Yashwanth) transmit silent telemetry to a central, Web3-authenticated forensic dashboard.

## 🚀 Key Features
Decentralized Node Monitoring: Real-time signal tracking across multiple simulated user accounts.

Web3 Authentication: Secure administrative access utilizing MetaMask wallet integration.

Silent Telemetry Protocol: Fraud detection signals are dispatched to the dashboard without alerting the suspect.

Node Suppression (Protocol Zero): Direct administrative control to revoke marketplace access for specific fraudulent entities.

## 🛡️ Simulated Fraud Vectors
This suite identifies three distinct high-risk behaviors:

Wardrobbing (Vishnu Rathan Node): Detecting usage wear and "event-based" return patterns for professional gear.

Item Not Received (Madhan Node): Flagging false non-delivery claims where tracking data confirms arrival.

Organized Return Ring (Yashwanth Node): Utilizing IP correlation to identify coordinated fraudulent activity across multiple accounts.

## 🛠️ Tech Stack
Core Logic: JavaScript (ES6+) utilizing asynchronous event handling and localStorage buffers.

UI/UX Design: Built with Tailwind CSS and FontAwesome, designed for a high-fidelity "Security Operations Center" aesthetic.

Security Layer: Web3.js / MetaMask API for administrative identity verification.

## 📂 File Structure
admin.html: The central forensic dashboard and command center.

marketplace.html: User node for Vishnu Rathan (Wardrobbing simulation).

madhan.html: User node for Madhan (INR simulation).

yashwanth.html: User node for Yashwanth (Organized Ring simulation).

## 🏁 Getting Started
Deploy: Host the files or open admin.html in a local browser.

Authenticate: Connect your MetaMask wallet to unlock dashboard controls.

Monitor: Open user nodes in separate tabs/devices to observe real-time telemetry dispatch.
