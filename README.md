# NETWORKWALKS-TARUN-SAHANI-B084-WK3-PM1-PM2-PASSWORD-CRACKING
Networkwalks Cybersecurity Internship – Week 3: Password Cracking using John the Ripper and Networkwalks Password Cracking Tools.


Trainee: Tarun Sahani
Internship: Networkwalks Cybersecurity Internship
Week: 03
Environment: Kali Linux on macOS using Oracle VirtualBox
Modules: W3-PM1 and W3-PM2

⸻

Overview

Week 3 focuses on password security and password recovery through practical exercises using John the Ripper and Networkwalks password-cracking tools.

The objective is to understand how password-protected files can be assessed, how password hashes are extracted, and how dictionary-based password recovery works.

W3-PM1 – Password Cracking with John the Ripper (JTR)

Objective

To understand PDF password hash extraction and password recovery using John the Ripper and its graphical interface, Johnny.

Tools Used

* Kali Linux
* John the Ripper
* Johnny
* PDF hash extraction utility

Practical Workflow

1. Obtained the provided password-protected PDF.
2. Extracted the PDF password hash.
3. Prepared the hash for John the Ripper.
4. Performed the password recovery exercise.
5. Verified the result by opening the PDF with the recovered password.

Screenshots

See WK3-PM1-JTR/screenshots/.

Observations

This practical demonstrates how password hashes can be used for offline password auditing and why weak passwords are vulnerable to dictionary attacks.

⸻

W3-PM2 – Password Cracking with Networkwalks Tools

Objective

To extract a password-protected PDF hash using the Networkwalks Hash Calculator and test it using the Networkwalks Password Cracker.

Tools Used

* Networkwalks Hash Calculator
* Networkwalks Password Cracker
* Kali Linux Firefox

Practical Workflow

1. Downloaded the provided file My Locked PDF1.pdf.
2. Uploaded the PDF to the Networkwalks Hash Calculator.
3. Extracted the PDF hash beginning with $pdf$.
4. Copied the complete hash.
5. Submitted the hash to the Networkwalks Password Cracker.
6. Executed the available dictionary-based attempt.

Result

The initial 100-word dictionary attempt completed without recovering the password. A successful password recovery has not yet been verified.

Screenshots

See WK3-PM2-Networkwalks-Tools/screenshots/.

⸻

Key Learnings

* Understanding password-protected PDF files.
* Understanding PDF password hashes.
* Learning the role of John the Ripper in password auditing.
* Using graphical and browser-based password assessment tools.
* Understanding dictionary-based password attacks.
* Recognising the importance of strong and unique passwords.

Conclusion

Week 3 provided practical exposure to password security assessment using John the Ripper and Networkwalks tools. The exercises demonstrated the importance of password complexity and the limitations of small dictionary-based attacks.

Note: Results documented here reflect the practical outcomes actually observed during the lab.