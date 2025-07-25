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

1. ping the machine to ensure that you can reach it
2. scan the machine for the open ports using nmap
3. connect to ftp port using telnet
4. login using root as the admin and leave the password black
