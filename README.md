Virtual Home Lab Setup

Objective

This project involved building a virtual home lab to gain hands-on experience in network management, security analysis, and attack detection. The setup simulated realistic attack scenarios and explored tools for analyzing and managing network traffic. By setting up and using this lab, I developed a foundational understanding of cybersecurity principles and techniques.

Skills Learned

-Configuration and management of virtual environments.

-Proficiency with Linux commands for network management.

-Network traffic analysis and interpretation using Wireshark.

-Basics of attack simulation and detection using tools like Nmap.

-Improved problem-solving skills in cybersecurity contexts.

Tools Used

-VirtualBox: Hosted and managed the virtual machines.

-Ubuntu Server: Used as the target for attack simulations.

-Kali Linux: Employed for conducting penetration tests and scans.

-Wireshark: Captured and analyzed network traffic during simulations.

-Nmap: Performed scans to simulate attacks.

Steps 
1. Installed VirtualBox and VMs
2. Created a host-only network for isolated communication between VMs
3. Conducted an nmap scan from Kali to Ubuntu and captured network traffic with Wireshark
   
Ref 1: Identify IP Address
![image](https://github.com/user-attachments/assets/405754dc-7bcd-4c42-b3b9-dd58f92df093)
-Retrieved IP address of Ubuntu to initialize attack from Kali

Ref 2: Nmap Scan Execution in Kali & Resulted Network Traffic in Ubuntu
![image](https://github.com/user-attachments/assets/1c20388f-4c60-420e-be93-56681b8dd7b8)
![image](https://github.com/user-attachments/assets/bc748164-9325-4ecf-a95b-0065328d541c)
-Pinged IP address of Ubuntu from Kali and launched Wireshark to display the captured network traffic after the attack.

Ref 3: Network Diagram
![image](https://github.com/user-attachments/assets/4a98a2fc-aeb7-4573-8a5b-90e92425e1f0)
-This shows a visual representation of the simulated attack from Kali to Ubuntu.


