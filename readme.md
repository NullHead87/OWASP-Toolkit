# ⚡ OWASP Security Toolkit

> A single-file web security lab assistant for penetration testing practice, CTF competitions, and security education.

![Version](https://img.shields.io/badge/version-2.0-00ff88?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![No Install](https://img.shields.io/badge/install-none_required-green?style=flat-square)

---

## 🚀 Quick Start

No installation, no dependencies, no server required.

```bash
# Just open in your browser
firefox owasp_toolkit_v2.html

# Or double-click the file
```

Works completely offline. All processing happens in the browser.

---

## 🧰 Tools Included

### Encoding & Crypto
| Tool | Description | OWASP |
|------|-------------|-------|
| Hash Generator | MD5, SHA1, SHA256, SHA512, Base64, OAuth reverse | A02 |
| Base64 / ROT13 | Encode, decode, ROT13 cipher | A08 |
| URL Encoder | Full/partial URL encoding, cheatsheet | A03 |
| JWT Analyzer | Decode tokens, forge alg:none, modify claims | A02 |
| OAuth Bypass | Juice Shop password calculator, PortSwigger payload | A07 |

### Injection
| Tool | Description | OWASP |
|------|-------------|-------|
| XSS Payloads | DOM, Reflected, Stored + custom builder + library | A03 |
| SQL Injection | UNION SELECT builder, SQLite enumeration payloads | A03 |
| XXE Payloads | File read, SSRF, OOB exfiltration | A03 |
| Pickle RCE | Python pickle payload generator | A08 |

### Attack Tools
| Tool | Description | OWASP |
|------|-------------|-------|
| CSRF PoC Builder | Auto-generate malicious HTML forms | A01 |
| Null Byte Bypass | File extension bypass via %2500 | A04 |
| Allowlist Bypass | Redirect bypass via query parameter trick | A08 |
| Email Truncation | 255-char email privilege escalation calculator | A10 |
| Reverse Shell Cheatsheet | 9 shell types with custom IP/Port | A08 |

### Recon & Analysis
| Tool | Description | OWASP |
|------|-------------|-------|
| Recon Checklist | robots.txt, hidden dirs, endpoint discovery | A04 |
| HTTP Method Tester | curl command builder for all HTTP methods | A07 |
| Response Analyzer | Security header analysis and misconfiguration detection | — |
| ffuf / Wordlist | Directory fuzzing command builder | — |
| Password Wordlist | Custom wordlist generator based on target info | — |

---

## 🏴 CTF Lab

The included `ctf_lab.html` is a standalone CTF training environment with **12 challenges** designed to practice the toolkit tools.

| Difficulty | Challenges | Points |
|------------|------------|--------|
| 🟢 Easy | 3 | 175 |
| 🟡 Medium | 5 | 850 |
| 🔴 Hard | 3 | 950 |
| 🔵 Insane | 1 | 500 |
| **Total** | **12** | **2475** |

### How to use the CTF Lab
1. Open `ctf_lab.html` in one browser tab
2. Open `owasp_toolkit_v2.html` in another tab
3. Read the challenge description and examine the provided data
4. Use the toolkit tools to find the flag
5. Submit flags in format `FLAG{...}`
6. Check the Writeups tab if you get stuck
7. Progress is saved in browser localStorage

---

## 📋 Use Cases

- **CTF competitions** — Quick access to common payloads and encoding tools
- **Lab environments** — Juice Shop, DVWA, HackTheBox, TryHackMe, PortSwigger
- **Penetration testing** — Payload generation, curl command building
- **Security education** — Learning OWASP Top 10 attack techniques
- **Bug bounty** — Payload library and CVSS reference

---

## 🔧 No Dependencies

- ✅ Pure HTML + vanilla JavaScript
- ✅ No Node.js, Python, or any runtime required
- ✅ No npm install, no pip install
- ✅ No API keys or .env files
- ✅ Works fully offline
- ✅ No data sent anywhere — everything runs in your browser

---

## 📁 Files

```
owasp-security-toolkit/
├── README.md
├── LICENSE
├── owasp_toolkit_v2.html    # Main toolkit (20 tools)
└── ctf_lab.html             # CTF training lab (12 challenges)
```

---

## ⚖️ Legal Disclaimer

> **This toolkit is intended for authorized penetration testing, CTF competitions, security research, and educational purposes only.**
>
> Using these tools against systems, networks, or applications without explicit written permission from the owner is **illegal** and may result in criminal prosecution.
>
> The authors assume no liability for any misuse of this software. You are solely responsible for ensuring that your use complies with all applicable laws and regulations.
>
> Always get written permission before testing any system you do not own.

---

## 📚 References

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP API Security Top 10](https://owasp.org/www-project-api-security/)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [HackTricks](https://book.hacktricks.xyz/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Built for security education. Use responsibly.*