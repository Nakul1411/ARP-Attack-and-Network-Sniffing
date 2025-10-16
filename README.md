
# ARP-Attack-and-Network-Sniffing
## Name: NAKUL R 
## Reg.no: 212223240102
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
<img width="1008" height="740" alt="image" src="https://github.com/user-attachments/assets/ae6ff574-7745-406f-a7cd-5e8bcd4a157c" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:
<img width="1617" height="845" alt="image" src="https://github.com/user-attachments/assets/6348f9e0-b705-4630-87e2-c863fbaaad61" />






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1601" height="723" alt="image" src="https://github.com/user-attachments/assets/7c51d2a0-02dd-4aaa-aa7a-b9dc343dff35" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
