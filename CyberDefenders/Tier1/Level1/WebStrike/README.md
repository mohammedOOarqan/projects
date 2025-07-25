# CyberDefenders - [Lab Name]

- **Difficulty:** [Easy / Medium / Hard]  
- **Category:** [DFIR / Threat Hunting / Windows Logs / PCAP Analysis / Malware Analysis]  
- **Date:** [YYYY-MM-DD]  

---

## 🧠 Objective

[Briefly state the goal of the lab. Example: Investigate suspicious activity in Windows logs to identify how a system was compromised.]

---

## 🛠️ Tools Used

- [Example: Event Viewer]
- [Example: Wireshark]
- [Example: Sigma rules + HELK]
- [Example: CyberChef]

---

## 📜 Summary of Tasks

| # | Task Description | Answer / Flag |
|---|------------------|----------------|
| 1 | What was the attacker's IP address? | `192.168.1.100` |
| 2 | What exploit was used? | `EternalBlue (MS17-010)` |
| 3 | What file did the attacker drop? | `shell.exe` |

_(Replace this table with only questions you're allowed to share publicly if the lab is not open-solution-friendly)_

---

## 📝 Key Observations

- The attacker used [protocol/tool] to [behavior observed].
- Lateral movement detected from [host A] to [host B].
- Suspicious file: `C:\Users\Public\shell.exe` with hash `[...]`.

---

## 🖼️ Screenshots

> Include screenshots for key findings if relevant.

---

## 💡 Lessons Learned

- Always monitor for suspicious parent-child process chains.
- Logging PowerShell commands can help in early detection.
- Consider enabling command line auditing and logging.

---

## 📂 Files (optional)

- `/screenshots/`
- `/notes/`
- `/exports/`

---

## 📚 References

- [MITRE ATT&CK - T1059: Command and Scripting Interpreter](https://attack.mitre.org/techniques/T1059/)
- [CyberDefenders Lab](https://cyberdefenders.org/labs/...)

---
