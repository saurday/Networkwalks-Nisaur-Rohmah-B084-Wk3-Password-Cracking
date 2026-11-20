# WK3-PM2: Password Cracking with NetworkWalks Tools

## Overview
This project task is part of **Week 3 – Project Module 2** of the Cybersecurity & Ethical Hacking program. The objective is to recover the password of a protected PDF file (`My Locked PDF1.pdf`) using two free online tools built by NetworkWalks: the **Hash Calculator** and the **Password Cracker**.

## Background
Password cracking is the process of recovering a password from stored or protected data. When a file such as a PDF, ZIP, or Office document is locked, its password is stored as a hash — a scrambled, one-way representation of the original password. To recover the password, the hash is extracted from the file and then run through a cracking tool that tries different candidate words (a dictionary/wordlist attack) until a match is found.

Both NetworkWalks tools run directly in the browser, requiring no installation, which makes this module a more beginner-friendly alternative to the JTR/Johnny workflow in Module 1.

## Task
Crack the password of the attached PDF file (`My Locked PDF1.pdf`) using the **NetworkWalks Hash Calculator** and **Password Cracker** tools on a Windows laptop.

## Tools Used
- [NetworkWalks Hash Calculator](https://networkwalks.com/hash-calculator/)
- [NetworkWalks Password Cracker](https://networkwalks.com/password-cracker/)

## Steps Performed
1. Downloaded the encrypted PDF file `My Locked PDF1.pdf` from the lab page.
2. Opened the NetworkWalks Hash Calculator and uploaded the locked PDF under the **PDF** tab.
3. Copied the full extracted hash value (starting with `$pdf$...`).
4. Opened the NetworkWalks Password Cracker and pasted the hash into the input field.
5. Uploaded a custom wordlist (`.txt`) to the Password Cracker.
6. Ran the attack using the uploaded wordlist until the password was successfully cracked.
7. Opened the locked PDF using the cracked password to verify success.

## Result
- **Cracked Password:** `password1`
- PDF successfully unlocked and opened.

## Screenshots

1. Hash extracted via Hash Calculator
<img width="960" height="504" alt="Screenshot 2026-11-20 160444" src="https://github.com/user-attachments/assets/fee2e43d-3ca4-4d96-9a1c-82ebd88a0f01" />


2. Hash pasted into Password Cracker
<img width="960" height="504" alt="Screenshot 2026-11-20 160526" src="https://github.com/user-attachments/assets/d34f07db-8355-4115-8267-a8692a5aad10" />


3. Wordlist uploaded
<img width="960" height="504" alt="Screenshot 2026-11-20 160526" src="https://github.com/user-attachments/assets/12c0fe60-9e75-4ca7-9a3b-7c68a77dca61" />

4. Password cracked successfully
<img width="960" height="504" alt="Screenshot 2026-11-20 161351" src="https://github.com/user-attachments/assets/8f76ab79-cba0-4b43-9438-fdc1fc5c4e7b" />

5. PDF opened with cracked password
<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/86e44825-4739-42fd-a3bd-8c28cee6f891" />

## Key Learnings
- How a PDF's password hash is extracted and formatted (`$pdf$...`) for cracking tools.
- How a wordlist/dictionary attack is used to match a hash against candidate passwords.
- The same dictionary-attack principle as JTR, demonstrated through a simpler, browser-based workflow.
- Reinforces the real-world risk of weak, dictionary-guessable passwords.

---
*Part of the Cybersecurity & Ethical Hacking Project Tasks – Week 3*
