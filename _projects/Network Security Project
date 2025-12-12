---
title: "Network Security Project"
---
This project demonstrates exploiting network services only for educational purposes.

It was a practical project for Network Security subject.
It was under the supervision of a certified teacher in my university AIU.
Unauthorized exploiting of network services is illegal and unethical. 
<br>
<br>
The objective of this project is to identify and exploit 
vulnerabilities in network services running on a Metasploitable 
virtual machine using the Metasploit Framework. The focus is 
on performing initial reconnaissance, discovering potential 
vulnerabilities, and executing exploits to gain unauthorized 
access to the target machine.

<br>

Components used in the project:
<br>1-VMware Workstation. 
<br>2-Metasploitable. 
<br>3-Kali Linux.

<br>

The initial step involved setting up the virtual environment to ensure 
network communication between the Kali Linux and Metasploitable 
virtual machines. 
Kali Linux and Metasploitable were downloaded and configured using 
VMwareWorkstation. 
<br>
To identify open ports, services, and versions running on the 
Metasploitable machine and detect potential vulnerabilities that can be 
exploited. 
We will use nmap which is a powerful network scanning tool used for 
discovering hosts and services on a computer network, as well as 
identifying vulnerabilities in services. 
<br>
determine whether any of these services have known vulnerabilities. 
This can be done by cross-referencing the service versions with known 
exploits by Using the vulners Script in Nmap. 

We are going to exploit the vsftpd so we use Metasploit and enter it by 
typing msfconsle.
<br>
We will choose the backdoor (exploit/unix/ftp/vsftpd_234_backdoor) 
because the backdoor exploit allows you to gain unauthorized access to 
the target system with root privileges. A DoS attack, on the other hand, 
only disrupts the availability of the target service. It does not provide 
access or control.
<br>
Post-Exploitation:
To ensure its successful we will get a command shell on the target 
system. And we will ask him whoami. This should return root indicating 
administrative privileges. And put ls to list all target’s directories
<br>
We can also gather sensitive information about user credentials located 
in /etc/passwd
<br><br>
Screenshots
{% include figure image_path="/assets/images/NetworkSecurity/ns1.png" caption="Exploiting Vulnerabilities" %}
{% include figure image_path="/assets/images/NetworkSecurity/ns2.png" caption="matching modules" %}
{% include figure image_path="/assets/images/NetworkSecurity/ns3.png" caption="Exploit backdoor" %}
{% include figure image_path="/assets/images/NetworkSecurity/ns4.png" caption="list all target’s directories" %}
{% include figure image_path="/assets/images/NetworkSecurity/ns5.png" caption="gather sensitive information about user credentials" %}


