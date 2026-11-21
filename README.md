# NETWORKWALKS - WEEK 3: PASSWORD CRACKING PRACTICAL LABS

## INTRODUCTION

This repository documents the completion of the two compulsory practical modules for Week 3 of the Networkwalks Cybersecurity Training Program. The practicals focused on password recovery using John the Ripper (JTR), Johnny GUI, and the Networkwalks online tools.

## PROJECT MODULE 1: JOHN THE RIPPER (JTR)

### 1. Introduction

John the Ripper is used to identify passwords from hashes. We used Johnny to manage the recovery of a protected PDF.

### 2. John the Ripper and Johnny Configuration

Johnny was configured to locate the John the Ripper executable.

![Config](Screenshot%202026-11-21%20220254.png)

### 3. PDF Hash Extraction

The protected PDF file was processed to extract the hash.

![Extraction](Screenshot%202026-11-21%20221843.png)

### 4. Hash File Preparation

The hash was saved in a text file named hash1.txt using Notepad.

![Hash Prep](Screenshot%202026-11-21%20223440.png)

### 5. Password Recovery Using Johnny

The hash was loaded into Johnny, and a session was started to recover the password.

![Recovery](Screenshot%202026-11-21%20225022.png)

### 6. PDF Verification

The recovered password successfully opened the protected PDF.

![Verification](Screenshot%202026-11-21%20225653.png)

## PROJECT MODULE 2: PASSWORD CRACKING WITH NETWORKWALKS TOOLS

### 1. Introduction

This method used the Networkwalks Hash Calculator and Password Cracker without needing extra software.

### 2. Accessing the Networkwalks Hash Calculator

The PDF file was uploaded to the browser-based Hash Calculator to generate the hash.

![Calculator](Screenshot%202026-11-21%20231143.png)

### 3. PDF Hash Extraction

The tool generated the PDF hash, beginning with $pdf$

![Extraction](Screenshot%202026-11-21%20231825.png)

### 4. Password Recovery Using Networkwalks Password Cracker

The hash was entered into the online cracker to recover the password.

![Online Recovery](Screenshot%202026-11-21%20234613.png)

### 5. PDF Verification

Successful access confirmed the recovery process worked.

## TOOLS AND LEARNING OUTCOMES

Tools included JTR, Johnny, Hash Calculator, and Windows 11. I gained experience in hash extraction and password security assessment.
