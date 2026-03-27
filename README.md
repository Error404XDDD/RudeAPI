# 💀 RudeAPI Ultimate | Public Documentation 💀

<img width="1408" height="768" alt="1774653672926" src="https://github.com/user-attachments/assets/cb4c9cfa-a8e1-4ae7-ac40-aaba00773e7d" />

![API Status](https://img.shields.io/website?down_color=red&down_message=offline&up_color=green&up_message=online&url=https%3A%2F%2Frudeapi.onrender.com%2F)
![Uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)
![Privacy](https://img.shields.io/badge/privacy-Zero%20Logs-blueviolet)

This repository contains the official documentation and usage guide for **RudeAPI**, a high-performance utility service for developers.

> **Note:** This is a documentation-only repository. The core engine is private to ensure security and prevent unauthorized clones.

---

## 🌐 Live Endpoint
The API is globally available at:  
`https://rudeapi.onrender.com`

---

## 🛠️ Available Tools (How to use)

All requests are `GET` and return `application/json`.

### 1. Password Generator
Get a military-grade random password.
- **Endpoint:** `/tools/password`
- **Params:** `length` (Optional, 8-64)
- **Try it:** `https://rudeapi.onrender.com/tools/password?length=24`

### 2. Hex ID Generator
Generate unique hexadecimal tokens for sessions or databases.
- **Endpoint:** `/tools/id`
- **Try it:** `https://rudeapi.onrender.com/tools/id`

### 3. SHA256 Hasher
Securely hash any string. No data is stored on our servers.
- **Endpoint:** `/tools/hash`
- **Params:** `text` (Required)
- **Try it:** `https://rudeapi.onrender.com/tools/hash?text=YourTextHere`

### 4. Rude Magic 8-Ball
Ask a question, get a blunt answer.
- **Endpoint:** `/tools/chance`
- **Params:** `question` (Required)
- **Try it:** `https://rudeapi.onrender.com/tools/chance?question=Should_I_quit?`

---

## 🛡️ Privacy & Security Manifesto

RudeAPI was built with a **"No Data"** philosophy:
1. **No IP Tracking:** We don't see or log your IP address.
2. **In-Memory Processing:** Data is processed in RAM and never touches a hard drive.
3. **No Database:** We have nowhere to store your secrets even if we wanted to.
4. **Encrypted Traffic:** All connections are forced through HTTPS.

---

## 📝 Terms of Use
- **Rate Limiting:** Don't be a jerk. Excessive spamming will result in a temporary block.
- **Commercial Use:** Free for personal projects. For high-volume commercial use, contact the admin.
- **Legal:** Use this tool at your own risk. We are not responsible for lost passwords or bad 8-ball advice.

---
**Maintained by the RudeAPI Team.** *If you find a bug, open an issue in this repository.*
