# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:
To explore network sniffing and ARP Attacks

## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands.

### ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a

## OUTPUT:
![image](https://github.com/Priya-Loganathan/ARP-Attack-and-Network-Sniffing/assets/121166075/0c6e5c07-f918-4e48-8060-7e56d40fba5e)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![image](https://github.com/Priya-Loganathan/ARP-Attack-and-Network-Sniffing/assets/121166075/d4c15539-a63b-4bac-8576-9381e6993ee7)

### dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/Priya-Loganathan/ARP-Attack-and-Network-Sniffing/assets/121166075/61d32b1d-cf6b-40f5-8c14-3586382b6b9b)

In Kali issue the following commands:sudo dsnifff

## OUTPUT:
### wireshark :
Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Priya-Loganathan/ARP-Attack-and-Network-Sniffing/assets/121166075/d94f0ac8-3224-490d-8535-3f8ce4a838ff)

### ettercap :
ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.
![image](https://github.com/Priya-Loganathan/ARP-Attack-and-Network-Sniffing/assets/121166075/1a7bb3fe-0aa3-44a2-ad09-04a8353ad9be)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
