# MiniProject
Gaining access to a web server and being anonymous using proxychains and tor services. Successful demonstration of planting a backdoor and gain root access to a webserver


Abstract -- In this project, an attempt is made by an ethical hacker to gain a root privilege access to a web server without revealing his/her identity. To achieve anonymity; proxychains and tor services are used. Initially, after enabling proxychains and tor, the information of the target server is secretly gathered by using port scanning with Nmap. Based upon the open ports and their versions of the services hosted by the target server, the malicious activities are planned. After anonymous scanning of a target server, we observed there is an open 21 port where ftp service of version vsftpd v2.3.4 is hosted. Finally, using the Metasploit tool the vulnerability of the above version is exploited, and the backdoor is planted on a target server, and root privileges are achieved successfully.
Keywords: proxychains, tor, Nmap, and Metasploit
