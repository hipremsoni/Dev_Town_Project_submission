

---

# 💥 Hack Like a Pro: Conquer the Ultimate CTF Battle!

## 🔐 Cybersecurity Lab Project: Penetration Testing with Nmap & Metasploit

**📝 Task:** Penetration Testing of *Basic Pentesting 1* Machine using Nmap and Metasploit
**🎓 Assigned by:** DevTown

---

## 🎯 Objective

Gain hands-on experience in penetration testing by:

* Scanning and identifying open ports using **Nmap**
* Detecting vulnerabilities on the target machine
* Exploiting the vulnerabilities using **Metasploit Framework**
* Gaining shell access to the target
* Documenting the entire process like a professional penetration test report

---

## 🧰 Tools Used

| Tool                | Purpose                                                      |
| ------------------- | ------------------------------------------------------------ |
| **Netdiscover**     | To identify the IP address of devices on the network         |
| **Nmap**            | For port scanning and service enumeration                    |
| **Metasploit**      | To exploit known vulnerabilities and gain shell access       |
| **Google Dorking**  | For information gathering using advanced search queries      |
| **Linux Commands**  | For post-exploitation enumeration and analysis               |
| **John the Ripper** | For cracking password hashes (optional step discussed)       |
| **Hashcat**         | Another tool for password cracking (optional step discussed) |

---

## 🧪 Task (POC)

```text
Proof of Concept (POC) is uploaded in this repository.
```

---

## 📌 Summary

* We began by identifying the target machine’s IP address using `netdiscover`.
* A comprehensive **Nmap scan** was conducted to discover:

  * Open ports
  * Running services
  * Operating system fingerprinting
  * SSL/TLS details and encryption info
* The scan showed that **FTP (ProFTPD 1.3.3c)**, **HTTP**, and **SSH** services were active.
* Using **Google Dorking**, we found that the FTP version had known vulnerabilities.
* We launched an exploit via **Metasploit Framework**, gaining remote shell access.
* With shell access, we read the `/etc/passwd` file to enumerate user accounts.
* We discussed cracking password hashes using **John the Ripper** or **Hashcat** for privilege escalation (theoretical).

---


