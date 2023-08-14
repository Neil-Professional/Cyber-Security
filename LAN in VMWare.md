### Download the following ISO images
Windows 10\
Kali Linux




### Set up DHCP Server on VirtualBox
From User Directory (eg: C:\Users\Joker>) \
cd / Program Files/Oracle/VirtualBox

From C:\Program Files/Oracle/Virtual> \
vboxmanage dhcpserver add --network=<Internal Server Name> --server-ip=10.38.1.1 --lower-ip=10.38.1.110 --upper-ip=10.38.1.120 --netmask=255.255.255.0 --enable

To confirm \
Ping 8.8.8.8
Ping Host IP
Ping Another Internal IP


