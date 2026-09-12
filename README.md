
# PROJECT-WORK-FOR-LAB-SETUP-WEEK-1-FOR-CYBERSECURITY
A Week 1 cybersecurity lab project focused on setting up a cybersecurity laboratory environment, configuring tools, and performing basic security exercises.
## 📃Project Introduction
**The PROJECT-WORK-FOR-LAB-SETUP-WEEK-1-FOR-CYBERSECURITY** is a practical cybersecurity project focused on establishing and configuring the basic tools and systems required for cybersecurity training and practical exercises. The project introduces the learner to a controlled laboratory environment where different cybersecurity concepts, tools, and techniques can be studied safely.

During Week 1, the main focus is on preparing the laboratory environment, installing and configuring the required software, understanding basic system and network settings, and ensuring that the tools are ready for future cybersecurity activities. This foundation will support practical learning in areas such as network security, system security, ethical hacking, digital forensics, and vulnerability assessment.

The project emphasizes hands-on learning and proper documentation of the setup process. By completing the laboratory setup, the learner will have a suitable environment for carrying out cybersecurity experiments while developing practical technical skills.
## 🥅Objective
It is designed to develop practical skills in areas such as network security, system security, vulnerability assessment, ethical security testing, and digital forensics. The laboratory also provides an environment where learners can safely experiment, troubleshoot problems, document their findings, and gain practical experience that can be applied to real cybersecurity situations.
The main objective of this project is to establish a functional cybersecurity laboratory for practical learning and security exercises.  
- Installing VirtualBox   
- Install KaliLinux in Virtual Machine  
- Configuringing Network Connectivity in the Kali VirtualBox Machine  
- Creating NAT Network for the **Lab**  
- Verifying DNS Server
## 📈Goal of the Lab
The Goal of the cybersecurity laboratory is to provide a safe and controlled environment for learning and practicing cybersecurity concepts. The lab allows me to install, configure, and test different cybersecurity tools without affecting real-world systems.  
## ⚙️Lab SetUp Implementation.  
## Guide 1. Downloading VirtualBox Machine.  
I downloaded and installed VirtualBox for Windows based on the operating system and specifications of the machine I am using. And the verions of VirtualBox is 7.2.16.  
<img width="497" height="387" alt="Virtual 7 2 16 installer" src="https://github.com/user-attachments/assets/ed1d588d-26e4-4c41-97c9-6a1ee9513684" /> <img width="1023" height="496" alt="Download Virtualbox" src="https://github.com/user-attachments/assets/9b2de168-b8d4-41e6-9ae4-ea34adbf5363" /><img width="1025" height="610" alt="VirtualBox" src="https://github.com/user-attachments/assets/1c0b0308-b54b-492d-9383-84f6814e61d7" />  
## Guide 2. Setting or Creating NATNetwork. 
I configured a NAT Network in VirtualBox to provide network connectivity for the virtual machines. I created the network using the name NatNetwork, enabled DHCP, and used the IPv4 network range 10.0.0.0/24. This configuration allows virtual machines in the cybersecurity lab to communicate through the NAT network while receiving IP addresses automatically.  
<img width="1360" height="682" alt="NATnetwork" src="https://github.com/user-attachments/assets/8f4526be-1527-41ba-99d1-11d97ecaba63" />  
## Guide 3. Starting or Running KaliLinux Inside VirtualBox Machine.  
### Starting Kali Linux Virtual Machine
I created and configured a **Kali Linux virtual machine** in VirtualBox and started it for the cybersecurity lab. I allocated **2 GB of RAM and 2 processors** and configured the network adapter to use the previously created **NAT Network (NatNetwork)** for network connectivity.
<img width="1357" height="695" alt="Starting Kalilinux" src="https://github.com/user-attachments/assets/5ad6b9d6-83b2-4f2b-9960-70f3711bb32e" />
<img width="1363" height="696" alt="KaliLinux Distop" src="https://github.com/user-attachments/assets/55b72c54-0038-4025-ba50-bad09ca6e4f8" />








