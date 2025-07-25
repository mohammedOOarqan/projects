# Hack The Box - Meow

- **Difficulty:** Easy  
- **Category:** Misconfiguration  

---

## 🔍 Vulnerability

Misconfiguration in the **Telnet** service allowed unauthenticated login as `root`.

---

## 🛠️ Tools Used

- `ping`
- `nmap`
- `telnet`

---

## 📸 Screenshots

> Below are the steps with screenshots included.

1. Ping to check connectivity  
   ![Ping Screenshot](./images/img1.png)

2. Nmap scan reveals open Telnet port  
   ![Nmap Scan](./images/img2.png)

3. Telnet login as root (no password)  
   ![Telnet Login](./images/img3.png)

4. Flag extraction  
   ![Flag Screenshot](./images/img4.png)

---

## 💡 Notes

- Default Telnet with root access is a major security risk.
- Always disable unused services and enforce authentication.

---
