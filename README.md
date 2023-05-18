Exploiting VSFTPD Backdoor:
The target system, Metasploitable 2, has multiple services running, including vsftpd 2.3.4, an FTP server. This version of vsftpd is vulnerable to a backdoor exploit known as "ftp/vsftpd_234_backdoor."

The malicious backdoor was introduced into the vsftpd-2.3.4.tar.gz archive sometime between June 30th, 2011, and July 1st, 2011. It was subsequently removed on July 3rd, 2011. Exploiting this backdoor can provide unauthorized access to the system.

To exploit this vulnerability, the Metasploit Framework can be utilized. Metasploit is a powerful open-source framework that aids in penetration testing and exploit development. It provides a wide range of exploits, including the one targeting the VSFTPD backdoor.

To proceed with the exploit, follow these steps:

Set up the payload in Metasploit:

Launch the Metasploit Framework.
Search for the "ftp/vsftpd_234_backdoor" exploit module.
Load the exploit module and set the required parameters, such as the target IP address and port.
Configure the payload:

Specify the desired payload, such as a reverse shell or a Meterpreter session.
Customize any additional settings or options as needed.
Execute the exploit:

Run the exploit within Metasploit.
If successful, the exploit will establish a direct connection to the target system with the privileges of the "root" user, granting complete control over the compromised system.
It is crucial to note that exploiting vulnerabilities without proper authorization and consent is illegal and unethical. This write-up should be used for educational and research purposes only, within the bounds of legal and ethical guidelines.
