# PFsense Deployment & Config

<img width="1109" height="809" alt="image" src="https://github.com/user-attachments/assets/9f4f298f-41eb-41b6-808f-a47267418a49" />



The purpose of this lab is to design and implement a controlled network environment to demonstrate the role of a firewall in protecting systems from malicious activity. Using pfSense as the virtual firewall, I will deploy and configure security policies to manage network traffic between virtual machines. The lab will consist of three key components: an Ubuntu server acting as the target machine, a Kali Linux system simulating an attacker, and pfSense positioned as the defensive layer between them. After configuring the pfSense firewall, I will initiate attacks from the Kali Linux machine against the Ubuntu system to observe vulnerabilities and then apply firewall rules in pfSense to detect and block the malicious traffic. This exercise highlights the importance of firewalls in network defense and provides practical experience with both offensive and defensive security concepts.

Our initial process starts with running our PFsense VM and getting the address in which we will use to access the web gui for configuration of the firewall. 

<img width="678" height="370" alt="image" src="https://github.com/user-attachments/assets/57d017e5-81c6-4cf7-ba20-f4f8555a6ede" />

Next we initiate the Ubuntu VM and login to the web-based gui from our firefox browser, we will do our initial configuration of the system and then disable the firewall in order to set our rules and make any other necessary changes. 

<img width="965" height="429" alt="image" src="https://github.com/user-attachments/assets/72bcba9b-99d8-4c43-b070-696e8b8d98b0" />











