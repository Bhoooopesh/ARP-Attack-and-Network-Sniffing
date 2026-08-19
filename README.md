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
<img width="831" height="620" alt="image" src="https://github.com/user-attachments/assets/7a442ad9-8d72-4cef-ad8f-2ef171cfd5d7" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="844" height="619" alt="image" src="https://github.com/user-attachments/assets/d8e01fe1-8aac-40a9-9e26-b805b356953f" />
<img width="869" height="646" alt="image" src="https://github.com/user-attachments/assets/01976c9b-f2f3-4d26-b2d9-4af9a1fb92d2" />








In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="844" height="637" alt="image" src="https://github.com/user-attachments/assets/675822dd-0814-4e15-8dbc-bba224fc9d90" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="851" height="627" alt="image" src="https://github.com/user-attachments/assets/995ba0e7-0671-48d0-859c-6f8158357abe" />


Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="840" height="600" alt="image" src="https://github.com/user-attachments/assets/ab409a69-b206-4183-8fc2-31b83756e036" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
