# Nmap-Penetration-testing-
Dropping about nmap command, penetration testing and scanning 

NMAP SCANNING
|
|
|
1.nmap --script=vuln -p 445 10.5.6.12
2.nmap -sA 10.5.6.12
3.nmap -sV 10.5.6.12  
4.nmap -sS 10.5.6.12
5.nmap -sP 10.5.6.12
6.nmap scanme.org
--------------------------METASPLOIT-----------------------------
For opening the METASPOLIT program the command is 'msfconsole' 
For help needed in metasploit the command is 'msfconsole -h'
When we write this of NMAP 'nmap --script=vuln -p 445 10.5.6.12' we get Host Script Results like ms01-90 etc.....so when it is opened we search for this host script results 
command is 'msf6 > search ms01-90' and thus we get the matching modules of this command 

---------------------General commands--------------------
-sn: Disables port scan.
-v: Enables the verbose output (include all hosts and ports in the output).
-sV: Detects service versions.
-A: Enables aggressive scan. The aggressive scan option supports OS detection (-O), version scanning (-sV), script scanning (-sC), and traceroute (--traceroute). You should not use -A against target networks without permission.
-p: Specifies the port to be scanned.
-O: OS detection.
-A: Aggresive detection 
-v: Verbosity detection  

We should download OWASP terminal on oracle box with the help of that we can get different different IP ADDR to practice the nmap tool with the help of OWASP we scan or ping the given addr and find vulnerbilites from the system  

here is the image u will get it 
![image](https://github.com/user-attachments/assets/ee5e5d17-474c-4cf2-b645-7ecd3f5e29d6)








