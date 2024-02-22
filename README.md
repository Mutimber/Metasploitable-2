# Metasploitable-2

## Objective
The lab introduces Metasploitable 2, a purposely vulnerable VM, guiding users through setup for ethical hacking practice. By downloading it from Rapid7 and configuring it with VirtualBox, along with setting up networking, users can safely explore security flaws. Additionally, it provides instructions on booting up Kali Linux, a common penetration testing OS.

### Skills Learned
1. Setting up virtual machines using VirtualBox.
2. Downloading and configuring vulnerable virtual machines like Metasploitable 2.
3. Configuring network settings to enable communication between virtual machines.
4. Basic usage of Kali Linux for penetration testing and vulnerability scanning.

### Tools Used
1. Virtualization platforms like VirtualBox or VMWare.
2. Metasploitable 2, a vulnerable virtual machine.
3. Kali Linux, a penetration testing operating system.
4. Network configuration tools within VirtualBox.

## Steps
1. Download Metasploitable 2 from Rapid7's SourceForge [link](https://sourceforge.net/projects/metasploitable/)
2. Create a new virtual machine profile in VirtualBox.
3. Import the Metasploitable.vmdk file into the virtual machine.
4. Boot up the Metasploitable 2 virtual machine and log in with default credentials.
5. Configure network settings in VirtualBox to enable communication between VMs.
6. Find the IP address of the Metasploitable 2 VM using ifconfig.
7. Test network connectivity by pinging the Metasploitable 2 VM from Kali Linux.
#### Figure 1: ifconfig on MS2 to find VM machine IP
![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/ffb3acdb-921e-47b2-b31b-69d729d5348b)

#### Figure 2: ping 10.0.2.4 on Kali VM to verify connectivity to Metasploit
![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/c8143701-6ef5-4860-af57-5653fb655bb6)

## Lab Quiz
1. Which company created Metasploit and Metasploitable 2?
   Rapid 7
2. How many TCP ports are OPEN on MS2? (Use the -sT flag in Nmap).
   23 open TCP ports
   ![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/28f90f99-c9f7-40b6-b84f-baeb684b08fa)
3. How many UDP ports are OPEN on MS2? (Use the -sU flag in Nmap – this may take a while). 7
   ![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/7283142e-bde3-441b-8987-6ecb52dbcee1)

4. What port is running a Metasploitable Root Shell? (Use the -sV flag in Nmap). 1524
   ![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/193e8bee-449e-41d2-87aa-eef89141e72e)

5. What non-standard port is FTP running on? (NOT p21) (Use the -sT flag in Nmap). 2121
   ![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/2e4dd879-0203-4c9a-b14e-fe81435ef261)

6. What version of FTP is running on the non-standard port? (Use the -sV flag in Nmap). ProFTPD 1.3.1
![image](https://github.com/Mutimber/Metasploitable-2/assets/113706552/d83b525c-cbe4-4e8f-9af8-2a19128c3e2e)
