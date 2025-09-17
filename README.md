# PFsense Deployment & Config

<img width="1109" height="809" alt="image" src="https://github.com/user-attachments/assets/9f4f298f-41eb-41b6-808f-a47267418a49" />



The purpose of this lab is to design and implement a controlled network environment to demonstrate the role of a firewall in protecting systems from malicious activity. Using pfSense as the virtual firewall, I will deploy and configure security policies to manage network traffic between virtual machines. The lab will consist of three key components: an Ubuntu server acting as the target machine, a Kali Linux system simulating an attacker, and pfSense positioned as the defensive layer between them. After configuring the pfSense firewall, I will initiate attacks from the Kali Linux machine against the Ubuntu system to observe vulnerabilities and then apply firewall rules in pfSense to detect and block the malicious traffic. This exercise highlights the importance of firewalls in network defense and provides practical experience with both offensive and defensive security concepts.

Our initial process starts with running our VirtualBox PFsesnse machine and getting our configuration settings through the cli. 

<img width="732" height="255" alt="image" src="https://github.com/user-attachments/assets/bf18edb6-4a57-4feb-b5fe-5f50e4b9a4c3" />

Next we initiate the Ubuntu VM and login to the web-based gui from our firefox browser, we will do our initial configuration of the system and then disable the firewall in order to make changes. 

<img width="965" height="429" alt="image" src="https://github.com/user-attachments/assets/72bcba9b-99d8-4c43-b070-696e8b8d98b0" />


From there I am logging in and adding Firewall rules 

<img width="1167" height="664" alt="image" src="https://github.com/user-attachments/assets/1144fb2c-5b24-45b4-8c7e-1c7660167016" />

Afterwards I create my rule to allow entry from my Kali linux machine.
<img width="629" height="220" alt="image" src="https://github.com/user-attachments/assets/0dd8770a-1020-41f5-a322-9660788fe921" />


<img width="1192" height="589" alt="image" src="https://github.com/user-attachments/assets/8006cfcd-feaa-4fe8-9309-c8a517fde702" />







