# WEEK 3 – PASSWORD CRACKING LABS

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-red" alt="Skill Cybersecurity">
  <img src="https://img.shields.io/badge/Ver-Virtualbox_v7.2.22-0078D4" alt="Virtualbox v7.2.22">
 <img src="https://img.shields.io/badge/Kali_Linux-v2025.1-orange" alt="Kali Linux v2025.1">
  <img src="https://img.shields.io/badge/Skill-Linux-red" alt="Skill Linux">
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-009688" alt="Network 10.0.0.0/24">
  <img src="https://img.shields.io/badge/Penetration_Testing-red" alt="Penetration Testing">
  <br>
  <img src="https://img.shields.io/badge/Skill-Virtualization-red" alt="Skill Virtualization">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Host-Parrot_OS-red" alt="Host Parrot OS">
  <img src="https://img.shields.io/badge/Ethical_Hacking-orange" alt="Ethical Hacking">
  <img src="https://img.shields.io/badge/-Mercy_Oyanimughan-CC0000" alt="Mercy Oyanimughan">
</p>

**Networkwalks Cybersecurity Internship | Batch B084D**

## Overview

This repository documents the practical exercises completed during Week 3 of the Networkwalks Cybersecurity Internship. The exercises focused on password recovery using John the Ripper and Networkwalks online password-cracking tools.

The objective was to understand how password hashes can be extracted, analysed and used in password recovery within an authorised lab environment.

## MODULE 1: PASSWORD CRACKING WITH JOHN THE RIPPER

### Objective
To use John the Ripper and its graphical interface, Johnny, to recover the password of a supplied password-protected PDF file.

### Tools Used
- Parrot Linux
- John the Ripper (Jumbo version)
- Johnny GUI
- PDF Hash Extractor

### Practical Steps
1. Checked the John the Ripper installation and build information.
2. Launched Johnny and explored its interface.
3. Verified the John the Ripper executable configuration through Johnny settings.
4. Extracted the password hash from the supplied PDF file.
5. Saved the extracted hash locally and loaded it into Johnny.
6. Initiated the password-cracking process.
7. Observed the successful cracking result.
8. Used the recovered password to open the protected PDF file.

### Result
The password recovery process was successful. John the Ripper reported that the hash had been cracked, and the supplied PDF was successfully opened.

### Screenshots
See the `Module-1-John-the-Ripper/Screenshots` folder.

---

## MODULE 2: PASSWORD CRACKING WITH NETWORKWALKS ONLINE TOOLS

### Objective
To use Networkwalks online tools to extract a PDF password hash and recover the password.

### Tools Used
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser

### Practical Steps
1. Downloaded the supplied password-protected PDF file.
2. Uploaded the PDF to the Networkwalks Hash Calculator.
3. Extracted and copied the generated password hash.
4. Opened the Networkwalks Password Cracker.
5. Submitted the extracted hash for password recovery.
6. Observed the recovered password.
7. Used the recovered password to open the protected PDF file.

### Result
The password recovery process was successful. The online password cracker recovered the password, and the supplied PDF was successfully opened.

### Screenshots
See the `Module-2-Networkwalks-Tools/Screenshots` folder.

---

## KEY LEARNINGS

- Understanding password hashes and their role in authentication.
- Extracting PDF password hashes for authorised security testing.
- Using John the Ripper and Johnny for password auditing.
- Using browser-based password recovery tools.
- Understanding the security risks associated with weak passwords.
- The importance of strong, unique passwords.

## ENVIRONMENT

- Operating System: Parrot Linux (Module 1)
- John the Ripper Version: 1.9.0 Jumbo
- Module 2: Browser-based Networkwalks tools

## DISCLAIMER

All practical exercises documented in this repository were performed as part of an authorised cybersecurity internship using the supplied training material. These techniques should only be used on files and systems for which permission has been granted.

**Note:** Recovered passwords, complete password hashes and sensitive training files have intentionally been excluded from this public repository.
