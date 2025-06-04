# File-Integrity-Monitor

File integrity monitoring (FIM), sometimes referred to as file integrity management, is a security process that monitors and analyzes the integrity of critical assets, including file systems, directories, databases, network devices, the operating system (OS), OS components and software applications for signs of tampering or corruption, which may be an indication of a cyberattack.

File Integrity Monitoring Use Cases: 
1) Detecting a cyberattack
2) Expediting threat detection, response and remediation
3) Identifying weaknesses within the IT infrastructure
4) Streamlining compliance efforts

How this FIM Tool works:
1) Defining the file integrity policy
   
   Before starting this FIM tool, the user must first specify what assets will be monitored and the types of changes that it wants to detect in powershell script.
   
2) Establishing a baseline
   
   When you run tool for the first time it will ask you create initial baseline, which will serve as a reference point for comparison for all future activity. This    will contain all file attributes, including file size, content, access settings, privileges, credentials and configuration values.
   
3) Applying the cryptographic hash signature
   
   As part of developing the baseline, the tool will also apply a cryptographic hash signature, which can’t be altered, to each file. Any changes made to the          files, whether authorized or not, will also change the hash value of the file, making it easy to detect file updates and alterations

4) Monitoring, analyzing and verifying file integrity
   
   The FIM tool compares the hash values on the files to quickly and clearly detect anomalous changes. 
   
5) Issuing an alert
   
   In the event an unexpected or unauthorized modification has been made, the FIM tool will also alert the individual on the given email for further investigation      and possible remediation

   
