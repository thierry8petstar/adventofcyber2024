### TryHackMe — Advent of Cyber 2024: Day 14: Be it ever so heinous, there’s no place like Domain Controller.

**Question 1: On what day was Glitch_Malware last logged in?**

**Answer:** 07/11/2024

**Question 2: What event ID shows the login of the Glitch_Malware user?**

**Answer:** 4624

**Question 3: Read the PowerShell history of the Administrator account. What was the command that was used to enumerate Active Directory users?**

**Answer:** Get-ADUser -Filter * -Properties MemberOf | Select-Object Name

**Question 4: Look in the PowerShell log file located in Application and Services Logs -> Windows PowerShell. What was Glitch_Malware's set password?**

**Answer:** SuperSecretP@ssw0rd!

**Question 5: Review the Group Policy Objects present on the machine. What is the name of the installed GPO?**

**Answer:** Malicious GPO - Glitch_Malware Persistence
