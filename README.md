
INTRUSION/SPAM DETETCTION SYSTEM

			CREATED BY :-  VEDANSH DEVNANI
				BATCH-11 | 590011977 
OBJECTIVES1 (TASKS PERFORMED) 
Libraries used :- os
A function is defined to scan a file for suspicious elements, making it modular and reusable. (scan_file)
•	The script defines two lists:
o	suspicious_extensions: Contains file extensions commonly associated with malware
o	suspicious_keywords: Contains keywords typically found in malicious scripts
•	Check if the File Exists:
	Functions used: os.path os.path.isfile(file_path)
	Ensures that the given file exists before proceeding with the scan

NOVELTY 
Efficient File Processing:
•	Reading files in binary mode ('rb') with a decoding mechanism (decode(errors='ignore')) makes the code adaptable for a variety of file types, while gracefully handling unsupported characters.
Practical Error Handling:
•	The inclusion of a try-except block ensures robust error handling
Dual-Level Detection:
•	It scans for suspicious file extensions typically associated with malware (eg.exe,.js,.vbs)
•	It checks the content of the file for suspicious keywords like eval(,exec(,powershell
•	These 2 levels combined analysis enhances the chances of possible intrusions (especially malware)
Targeted Keyword Search:
•	Keyword search increases the chances of detecting intrutions
APPLICATIONS OF THIS PROJECT 

Malware Detection in Personal Computers
•	Users can run this script to scan suspicious files before opening them.
•	Helps detect scripts (.js, .vbs) or executables (.exe) that may contain malicious code.
2. Email Attachment Scanning
•	Email servers or security tools can use this logic to scan attachments for harmful content before allowing downloads.
•	Detects scripts with dangerous keywords like eval() or powershell that may execute malicious commands.
3. Automated Security Monitoring in Enterprises
•	IT security teams can integrate this into automated scans to detect unauthorized scripts or executables in shared drives.
•	Helps prevent insider threats or accidental execution of malicious files.
4. Web Server Upload Scanning
•	If a website allows file uploads (e.g., forums, cloud storage), this script can check for dangerous files before storing them.
•	Prevents attackers from uploading backdoors (e.g., PHP shells, malicious .js files).
5. Forensic Analysis in Cybersecurity
•	Incident responders can use this to quickly identify suspicious files during a malware investigation.
•	Detects obfuscated scripts (e.g., JavaScript using eval() for code execution).





FUTURE SCOPE

1) Prevents scammers in attacking the illiterate , the poor, the elderly 
2) Can be further used and modified to add more features and extensive use 

CODE

 

INPUT

 


FILE CONTENT
 


OUTPUT
 



DRAWBACKS
. 1) The code does not always read the file path and may give the output as undetected 
FIX TO THE PROBLEM
DISCLAIMER:- THIS CODE IS TO BE EXCECUTED SEPERATELY AND WORKS BEST FOR SPAM MAILS 
 

 


GITHUB LINK











 
















