# CyberDefenders - [WebStrike]
  
[the link to the labe](https://cyberdefenders.org/blueteam-ctf-challenges/webstrike/)

 
---

## 🧠 Objective

know the sorce of the attack and the name of the file the attacker was trying to get

---

## 🛠️ Tools Used

- [Wireshark]

---

## 📜 Summary of Tasks



1. [you will open the pcap file and will notice two primary ip addresses one for the attacker and the other for the server](images.img1.png)
2. [put the ip in ipgeolocation website to figure from where the attack happened](images.img2.png)
3. [open the http stream to know the user-Agent of the attacker](images.img3.png)
4. [scroll in the http request and you will find that one of the post request he was sending was succesfull this is the name of the webshell uploaded](images.img4.png)
5. [in the same http request in the body you can see the code of the webshell and what ip address and port it is trying to connect to](images.img5.png)
6. [open the tcp stream of the request from the server on the ip and port listed in the webshell and you will find a code that trying to send the passwd file](images.img6.png)
