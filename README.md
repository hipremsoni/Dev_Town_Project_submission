

# 💥 Hack Like a Pro: Conquer the Ultimate CTF Battle!

## 🔐 Cybersecurity Lab Project: Penetration Testing with Nmap & Metasploit

**📝 Task:** Penetration Testing of *Basic Pentesting 1* Machine using Nmap and Metasploit
**🎓 Assigned by:** DevTown

---

## 🎯 Objective

Gain hands-on experience in penetration testing by:

* Scanning and identifying open ports using **Nmap**
* Detecting vulnerabilities on the target machine
* Exploiting the vulnerabilities using **Metasploit (msfconsole)**
* Gaining shell access to the target
* Documenting the entire process like a professional penetration test report

---

## 🧪 Task (POC)

```text
Proof of Concept (POC) is uploaded in this repository.
```

---

## 📌 Summary

* The task began with identifying the target IP using `netdiscover`.
* We then performed a detailed scan using **Nmap** to gather information such as:

  * Open ports
  * Running services
  * Operating system details
  * Encryption keys
* The scan revealed that **FTP (ProFTPD 1.3.3c)**, **HTTP**, and **SSH** services were active.
* The FTP service was vulnerable. We used **Metasploit** to exploit it and successfully gained shell access.
* After obtaining access, we examined the `/etc/passwd` file for user account information.
* Password cracking techniques using **John the Ripper** or **Hashcat** were also discussed as part of the post-exploitation phase.

---

