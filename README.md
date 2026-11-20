NETWORKWALKS-CINDY-B084-WK3-PASSWORD-CRACKING

<div align="center">

PDF Password Recovery & Hash Cracking

Week 3 Project — NetworkWalks B084

</div>
<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-Lab-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/OS-Windows-0078D4?style=flat-square&labelColor=000000&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Tool-Johnny%20%7C%20John%20the%20Ripper-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Password%20Security-PDF%20Testing-E87500?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/NetworkWalks-B084-C00000?style=flat-square" />
</p>

⸻

Project Overview

This repository contains documentation of my Week 3 cybersecurity practical assignment at NetworkWalks, which focused on PDF password recovery and hash cracking.

The exercise introduced me to how password-protected files can be examined through their hashes and how password-cracking tools can be used to test the strength of file protection.

I carried out two practical tasks on a Windows computer. In the first task, I generated a PDF hash online, saved it in a text file, and used Johnny (John the Ripper’s graphical interface) to recover the password. In the second task, I used NetworkWalks’ own hash generator and password-cracking platform to recover another PDF password and complete the CTF challenge.

This exercise gave me a better understanding of how password protection can be evaluated and why using strong passwords is important.

⸻

OBJECTIVES & TOOLS

The main objectives of this project were to:

* Understand the relationship between password-protected files and password hashes.
* Explore how PDF hashes can be generated for password security testing.
* Use an online hash generator to extract the hash of a protected PDF.
* Save hash information in a text file using Notepad.
* Familiarize myself with Johnny’s graphical interface.
* Understand the role of John the Ripper in password recovery.
* Use a password-cracking tool to test a PDF hash.
* Practice PDF password recovery using the NetworkWalks platform.
* Complete a Capture The Flag (CTF) task through the password recovery exercise.
* Recognize the importance of password strength and file protection.

Tools and Technologies Used

Tool	Purpose
Windows	Computer operating system used to carry out the practical exercises.
Online Hash Crack	Used to generate the hash from the first password-protected PDF file.
Notepad	Used to store the generated hash in a text file for later use.
Johnny	Graphical interface used to interact with John the Ripper during the password recovery process.
John the Ripper	Used to analyse the supplied hash and attempt to recover the PDF password.
NetworkWalks Hash Generator	Used to generate the hash of the second protected PDF file.
NetworkWalks Password Cracker	Used to process the second hash and complete the password recovery challenge.

⸻

PRACTICAL IMPLEMENTATION

EXERCISE 1: RECOVERING A PDF PASSWORD WITH JOHNNY (JOHN THE RIPPER)

Step 1 — Extracting the PDF Hash Online

I began the first exercise by selecting a password-protected PDF file and using the Online Hash Crack website to generate its hash.

The hash serves as the input for the password recovery process, allowing the cracking tool to work on the password without repeatedly opening the original document.

Screenshot 1: Generating the PDF Hash Online

Explanation: This screenshot shows the online tool generating the hash from the first encrypted PDF file.

Step 2 — Copying the Hash into Notepad

Once the hash was generated, I copied the hash text and opened Notepad on my Windows computer.

I pasted the hash into the text editor and saved it as a text file. This file was then ready to be used as input for Johnny.

Screenshot 2: Hash Stored in Notepad

Explanation: This image shows the extracted hash stored in Notepad before it was loaded into the cracking application.

Step 3 — Preparing Johnny for the Test

I launched Johnny and loaded the hash file I had saved earlier.

The interface allowed me to prepare the hash for analysis and view the available options before starting the password recovery attempt.

Screenshot 3: Importing the Hash into Johnny

Explanation: The screenshot displays Johnny with the hash file loaded and prepared for the password recovery task.

Step 4 — Running the Password Recovery Process

With the hash loaded, I started the password recovery process.

John the Ripper examined the hash and attempted to identify the password that could unlock the protected PDF file. I monitored the process through Johnny’s graphical interface.

Screenshot 4: Password Recovery in Progress

Explanation: This screenshot captures the password analysis process as Johnny attempts to recover the password associated with the hash.

Step 5 — Confirming the Recovered Password

The process eventually returned a successful password recovery result for the first PDF.

This marked the completion of the first exercise and demonstrated how a password-protected file can be assessed using hash-based password recovery techniques.

Screenshot 5: Password Recovery Result

Explanation: The image shows the successful result returned after the first PDF password recovery attempt.

⸻

EXERCISE 2: PASSWORD RECOVERY USING THE NETWORKWALKS PLATFORM

Step 1 — Creating Another PDF Hash

For the second part of the assignment, I worked with a different password-protected PDF file.

This time, I used the NetworkWalks Hash Generator rather than the online hash generator from the previous exercise. The tool converted the protected PDF into a hash that could be used for the next stage of the challenge.

Screenshot 6: NetworkWalks PDF Hash Generator

Explanation: This screenshot shows the second PDF being processed through the NetworkWalks hash generation tool.

Step 2 — Submitting the Hash for Password Testing

After obtaining the hash, I moved to the NetworkWalks Password Cracker.

I provided the generated hash to the platform, which then carried out the password recovery process to determine the password associated with the second PDF.

Screenshot 7: NetworkWalks Password Cracker

Explanation: This image shows the hash being used in the NetworkWalks password recovery interface.

Step 3 — Completing the CTF Challenge

The second password recovery task was completed successfully.

After obtaining the required result, I proceeded to capture the flag, marking the successful completion of the challenge.

Screenshot 8: CTF Completion

Explanation: This screenshot provides evidence of the successful password recovery and the completion of the Capture The Flag task.

⸻

KEY LEARNING OUTCOMES

This practical exercise helped me develop a better understanding of the following concepts:

* Hash Generation: Learning how a password-protected PDF can be converted into a hash for security testing.
* Password Recovery: Understanding how password-cracking tools attempt to identify the password associated with a hash.
* John the Ripper: Gaining exposure to a tool used in password security assessment.
* Johnny Interface: Familiarizing myself with the graphical environment used to manage and monitor password recovery.
* File Handling: Learning how hash information can be copied, stored in text format, and prepared for use by another application.
* Windows Security Tools: Carrying out the exercise using a Windows-based working environment.
* CTF Participation: Applying the knowledge gained to complete a practical password recovery challenge.
* Security Awareness: Recognizing the need for strong passwords to prevent unauthorized access to sensitive documents.

⸻

CONCLUSION

The Week 3 practical provided me with an opportunity to explore password recovery and hash analysis using a Windows computer.

In the first exercise, I generated a PDF hash online, saved it in Notepad, and used Johnny with John the Ripper to recover the password of the protected document.

In the second exercise, I used the NetworkWalks Hash Generator and Password Cracker to work on another protected PDF and successfully complete the CTF challenge.

These exercises helped me appreciate how password security can be tested in a controlled environment and why users should avoid weak or easily guessed passwords when protecting important files.

⸻

LAB SAFETY & AUTHORIZATION

All activities documented in this project were performed as part of an authorized cybersecurity training exercise.

The techniques demonstrated are intended for educational purposes and should only be used on files, systems, or resources that you own or have permission to test.

⸻

AUTHOR

Gyamfi Cindy Fosuaa

Cybersecurity Intern — NetworkWalks

Batch: B084

LinkedIn: Gyamfi Cindy Fosuaa

⸻

<div align="center">

NetworkWalks | Cybersecurity Training | Week 3 Project

</div>