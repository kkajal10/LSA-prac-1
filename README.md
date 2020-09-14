# LSA-prac-1
A DHCP Server is a network server that automatically provides and assigns IP addresses, default gateways and other network parameters to client devices. It depend on the standard protocol known as Dynamic Host Configuration Protocol or DHCP to respond to broadcast queries by clients.
sudo apt-get update
sudo apt-get install isc-dhcp-server(required package)
ifconfig(for net ,netmask address)
sudo nano /etc/default/isc-dhcp-server(for changing domain name and)
cd /etc/dhcp(creating directory)
ls
sudo nano /etc/dhcp/dhcpd.conf(for changing net ,netmask and range)
sudo systemctl start isc-dhcp-server
sudo systemctl status isc-dhcp-server
sudo systemctl enable isc-dhcp-server
