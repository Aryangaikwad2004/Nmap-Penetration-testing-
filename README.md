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
