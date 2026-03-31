# HashSec 🔐
> Hash Generator & Identifier — A lightweight cybersecurity tool that runs entirely in your browser.

---

## 🛡️ About

**HashSec** is a simple, single-file cybersecurity tool for generating and identifying cryptographic hashes. No installations, no dependencies, no backend — just open `index.html` in any browser and it works.

Built as part of a cybersecurity portfolio by [MohammedAslam615](https://github.com/MohammedAslam615).

---

## ✨ Features

### Hash Generator
- Supports **MD5, SHA-1, SHA-224, SHA-256, SHA-384, SHA-512**
- Select any combination of algorithms at once
- One-click **copy** button for each hash result
- Character counter for input text

### Hash Identifier
- Paste any unknown hash to **auto-detect** the algorithm
- Identifies hashes by length, bit size, and prefix
- Supports: `MD5`, `SHA-1`, `SHA-2 family`, `bcrypt`, `NTLM`, `Unix crypt ($1$, $5$, $6$)`
- Shows **confidence level** and security notes for each result

### Privacy First
- 🔒 All processing is done **100% locally** in your browser
- No data is sent to any server
- No tracking, no cookies, no internet required after page load

---

## 🚀 Usage

### Option 1 — Open Directly
```bash
# Just open the file in your browser
open index.html
```

### Option 2 — GitHub Pages
Visit the live version at:
```
https://MohammedAslam615.github.io/hashsec
```

---

## 📸 Supported Hash Algorithms

| Algorithm | Output Length | Status |
|-----------|--------------|--------|
| MD5 | 32 hex chars (128-bit) | ⚠️ Broken — avoid for security |
| SHA-1 | 40 hex chars (160-bit) | ⚠️ Deprecated since 2017 |
| SHA-224 | 56 hex chars (224-bit) | ✅ Secure |
| SHA-256 | 64 hex chars (256-bit) | ✅ Industry standard |
| SHA-384 | 96 hex chars (384-bit) | ✅ Secure |
| SHA-512 | 128 hex chars (512-bit) | ✅ Strongest SHA-2 |

---

## 🔍 Hash Identifier Coverage

| Hash Type | Detection Method |
|-----------|-----------------|
| MD5 / NTLM | 32-char hex |
| SHA-1 | 40-char hex |
| SHA-224 | 56-char hex |
| SHA-256 / Keccak-256 | 64-char hex |
| SHA-384 | 96-char hex |
| SHA-512 | 128-char hex |
| bcrypt | `$2$` / `$2a$` / `$2b$` prefix |
| MD5 crypt | `$1$` prefix |
| SHA-256 crypt | `$5$` prefix |
| SHA-512 crypt | `$6$` prefix |

---

## 🗂️ Project Structure

```
hashsec/
├── index.html      # The entire tool — self-contained single file
└── README.md       # This file
```

---

## 🛠️ Built With

- **Vanilla HTML / CSS / JavaScript** — zero frameworks
- **Web Crypto API** — native browser API for SHA hashes
- **Pure JS MD5** — client-side MD5 implementation
- **JetBrains Mono & Rajdhani** — fonts via Google Fonts

---

## 👤 Author

**Mohammed Aslam**
SOC Analyst & Penetration Tester

- GitHub: [@MohammedAslam615](https://github.com/MohammedAslam615)

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

> *"The best defenders think like attackers."*
