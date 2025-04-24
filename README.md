# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![1](https://github.com/user-attachments/assets/8a331aa3-4e9f-4e06-9dbc-7e47464c2d73)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/user-attachments/assets/40ae5b66-4c09-4747-a8bd-4bff3f997409)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/user-attachments/assets/2e768a56-9150-4bfd-b4bd-549468690cc6)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/75d88f84-045b-4ee2-a93e-be6e56454ec7)

Invoke the wireshark and examine the various menus  and controls of the tool:
![4](https://github.com/user-attachments/assets/ccfbd412-b2de-4715-9251-fb3420851422)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
