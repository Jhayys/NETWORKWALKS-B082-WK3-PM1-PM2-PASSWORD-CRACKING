# PM1 – Password Cracking with John the Ripper

## 1. Project Overview
This project demonstrates password recovery from encrypted PDF files using John the Ripper and its graphical interface, Johnny, in Kali Linux.

## 2. Objectives
- Understand PDF password hash extraction.
- Learn how to use John the Ripper for password auditing.
- Practise password recovery in a controlled lab environment.
- Compare command-line and graphical password-cracking workflows.

## 3. Tools Used
- Kali Linux
- pdf2john
- John the Ripper
- Johnny GUI

## 4. Practical Activities
1. Extracted password hashes from three encrypted PDF files using pdf2john.
2. Saved the extracted hashes into individual text files.
3. Used John the Ripper to perform password recovery.
4. Verified recovered passwords using the `john --show` command.
5. Loaded the hash files separately into Johnny.
6. Observed a 100% cracked result in Johnny.

## 5. Results
All three PDF password hashes were successfully recovered in the controlled lab environment. The recovered passwords were used to verify access to the protected PDF files.

## 6. Security Lessons
- Weak PDF passwords can be vulnerable to offline password attacks.
- Strong, unique passwords improve document security.
- Password hashes should be protected from unauthorised access.
- Password auditing should only be performed with permission.

## 7. Conclusion
This exercise provided practical experience with PDF hash extraction and password recovery using both command-line and graphical tools in Kali Linux.

**Note:** Screenshots are provided as supporting evidence. Sensitive password and hash values have been excluded from the public documentation.
