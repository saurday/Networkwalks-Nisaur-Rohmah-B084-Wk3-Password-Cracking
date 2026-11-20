# WK3-PM1: Password Cracking with JTR (John the Ripper)

## Overview
This project task is part of **Week 3 – Project Module 1** of the Cybersecurity & Ethical Hacking program. The objective is to recover the password of a protected PDF file (`My Locked PDF1.pdf`) using **John the Ripper (JTR)** and its GUI version, **Johnny**, on a Windows PC.

## Background
John the Ripper (JTR) is a widely used password cracking and auditing tool, originally built for Unix systems and now available on Windows, Linux, and macOS. It supports many hash types and can crack passwords on protected files such as PDF, ZIP, and Office documents. Johnny provides a graphical interface on top of JTR, making it accessible for beginners without needing to type command-line syntax.

This exercise demonstrates how password hashes are extracted from protected files and cracked via dictionary-based attacks, reinforcing why strong, unique passwords are essential for security.

## Task
Crack the password of the attached PDF file (`My Locked PDF1.pdf`) using **JTR John** and **JTR Johnny** tools on a Windows PC.

## Tools Used
- [John the Ripper](https://www.openwall.com/john/)
- [Johnny GUI](https://openwall.info/wiki/john/johnny)
- [Online Hash Crack – PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php)

## Steps Performed
1. Downloaded John the Ripper and Johnny GUI, then installed Johnny on Windows.
2. Downloaded the encrypted file `My Locked PDF1.pdf`.
3. Extracted the PDF hash using the Online Hash Crack PDF Hash Extractor tool (format: `$pdf$...`).
4. Saved the extracted hash into a text file (`hash1.txt`).
5. Configured Johnny by setting the path to `john.exe`.
6. Opened `hash1.txt` as the password file in Johnny.
7. Started the attack and waited for the password to be cracked.
8. Opened the encrypted PDF using the cracked password to verify success.

## Result
- PDF successfully unlocked and opened.

## Screenshots

1. Hash extraction from PDF
<img width="960" height="504" alt="Screenshot 2026-11-20 150316" src="https://github.com/user-attachments/assets/965e1f01-cc24-4b5f-a3a0-fdc8f28367f1" />

2. Hash saved in `hash1.txt`
<img width="960" height="505" alt="image" src="https://github.com/user-attachments/assets/99cd1c52-a18e-4cc2-a9c7-82dfe26ae500" />
3. Johnny configured with `john.exe`
<img width="960" height="504" alt="Screenshot 2026-11-20 150837" src="https://github.com/user-attachments/assets/d211ebb2-a758-4698-b15a-261af515a832" />
4. Attack in progress
<img width="960" height="504" alt="Screenshot 2026-11-20 150944" src="https://github.com/user-attachments/assets/a37c827f-2fb1-45c5-b562-959491da9da9" />
5. Password cracked successfully
<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/ef06af22-99eb-4a7e-a4fd-6b91072168a1" />
6. PDF opened with cracked password
<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/0f44890d-e4e3-4f70-bfd9-0b1e287f6397" />

## Key Learnings
- How passwords stored in protected files are represented as hashes.
- The difference between encryption (two-way, reversible) and hashing (one-way, irreversible).
- Why weak/common passwords can be cracked quickly using dictionary attacks.
- Practical use of both CLI (John) and GUI (Johnny) password auditing tools.

---
*Part of the Cybersecurity & Ethical Hacking Project Tasks – Week 3*
