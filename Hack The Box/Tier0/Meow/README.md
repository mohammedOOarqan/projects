# Hack The Box - [Meow]

- **Difficulty:** Easy
- **Category:** Misconfiguration

---

## 🔍 Vulnerability

Misconfiguration in the **FTP** service allowed anonymous login and access to sensitive files.

---

## 🛠️ Tools Used

- `nmap`

---

## 📜 Steps to Exploit

### 1. Nmap Scan

```bash
nmap -sV -sC -oN nmap.txt x.x.x.x
