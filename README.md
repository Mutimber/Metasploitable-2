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

