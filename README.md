# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows


### Step 3:

Open terminal and try execute some kali linux commands

## ARP Attacks:  

ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

**In windows 7 give the command arp -a**


![exp4_1](https://github.com/Skanthasishanth/ARP-Attack-and-Network-Sniffing/assets/118298456/3d02b562-a539-4591-b9d9-7f18098aba8f)


### From kali linux issue the command :

**sudo arpspoof -i eth0 -t <target system> <gateway>**


![exp4_2](https://github.com/Skanthasishanth/ARP-Attack-and-Network-Sniffing/assets/118298456/8fc9b329-5a3e-4036-9d7b-c13397f72773)


### dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites **ftp.vim.org**


![exp4_3](https://github.com/Skanthasishanth/ARP-Attack-and-Network-Sniffing/assets/118298456/7f063c09-5eb6-4adc-9447-1f759d622ea7)


## WIRESHARK :

Invoke the wireshark and examine the various menus  and controls of the tool:

![exp4_4](https://github.com/Skanthasishanth/ARP-Attack-and-Network-Sniffing/assets/118298456/a2609089-5108-4d27-9953-4e80883275e6)


## ETTERCAP :

Ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.

![exp4_5](https://github.com/Skanthasishanth/ARP-Attack-and-Network-Sniffing/assets/118298456/6399f802-6818-45c0-a6cf-c91c1cbe4b91)


## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully
