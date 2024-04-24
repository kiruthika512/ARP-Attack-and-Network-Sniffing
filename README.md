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
![out1](https://github.com/kiruthika512/ARP-Attack-and-Network-Sniffing/assets/135616605/4139837d-9922-4410-b793-49dbb0577789)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![out2](https://github.com/kiruthika512/ARP-Attack-and-Network-Sniffing/assets/135616605/046192ba-5db1-40dc-b979-35570036836a)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![out3](https://github.com/kiruthika512/ARP-Attack-and-Network-Sniffing/assets/135616605/9ed2de05-28ad-41b4-82d8-9f9f1bfc40cf)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![out4](https://github.com/kiruthika512/ARP-Attack-and-Network-Sniffing/assets/135616605/fa9bc949-c7e2-428d-b7a9-7d9cd94d3679)




Invoke the wireshark and examine the various menus  and controls of the tool:

![out5](https://github.com/kiruthika512/ARP-Attack-and-Network-Sniffing/assets/135616605/2245f67b-98d3-4034-a492-e5b40f62efb3)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
