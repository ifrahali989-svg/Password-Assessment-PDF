# Password-Assessment-PDF
Practical cybersecurity lab demonstrating AI-assisted password recovery using John the Ripper (JTR) integrated via the HexStrike Model Context Protocol (MCP) server in a Kali Linux environment.
# Password Cracking with JTR + AI (HexStrike MCP Edition)

A practical cybersecurity lab demonstrating AI-assisted password recovery using John the Ripper (JTR) integrated via the HexStrike Model Context Protocol (MCP) server in a Kali Linux environment.

## Lab Overview
* **Objective:** Crack the password of a secured PDF file (`networkwalks_flag1.pdf`) using John the Ripper and the `rockyou.txt` dictionary.
* **Environment:** Kali Linux virtual machine running a HexStrike AI server with JTR (`1.9.0-jumbo-1+bleeding-aec1328d6c`).
* **Methodology:**
  * Verified tool installation and health status via HexStrike MCP.
  * Computed cryptographic hash values (MD5, SHA-1, SHA-256) for the target PDF file.
  * Executed a dictionary-based attack utilizing the `rockyou.txt` wordlist (`~14.3 million entries`).
* **Result:** Successfully cracked the password (`password1`) instantly on the first dictionary match.

* [PDF-Password-Assessment.pdf](https://github.com/user-attachments/files/34986199/PDF-Password-Assessment.pdf)
