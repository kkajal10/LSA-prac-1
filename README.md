# LSA-prac-1
A DHCP Server is a network server that automatically provides and assigns IP addresses, default gateways and other network parameters to client devices. It depend on the standard protocol known as Dynamic Host Configuration Protocol or DHCP to respond to broadcast queries by clients.
1)sudo apt-get update
2)sudo apt-get install isc-dhcp-server(required package)
3)ifconfig(for net ,netmask address)
4)sudo nano /etc/default/isc-dhcp-server(for changing domain name and)
5)cd /etc/dhcp(creating directory)
6)ls
7)sudo nano /etc/dhcp/dhcpd.conf(for changing net ,netmask and range)
8)sudo systemctl start isc-dhcp-server
9)sudo systemctl status isc-dhcp-server
10)sudo systemctl enable isc-dhcp-server
